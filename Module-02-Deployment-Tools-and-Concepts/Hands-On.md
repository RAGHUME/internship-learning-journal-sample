# 🛠️ Week 2 – Hands-On Practice

## 🔹 1. Install Docker (WSL)

```bash
sudo apt update
sudo apt install docker.io -y

Start Docker:

sudo systemctl start docker
sudo systemctl enable docker
🔹 2. Verify Installation
docker --version
🔹 3. Pull Image
docker pull jupyter/base-notebook
🔹 4. List Images
docker images
🔹 5. Remove Image
docker rmi <image_id>
🔹 6. Run Container
docker run <image_id>

Detached mode:

docker run -d <image_id>

With name:

docker run -d --name mycontainer <image_id>
🔹 7. View Containers
docker ps

Stop container:

docker stop <container_id>
🔹 8. Port Mapping
docker run -d -p 8888:8888 --name mycontainer <image_id>

Logs:

docker logs mycontainer
🔹 9. Volume Mounting
docker run -d \
  -p 8888:8888 \
  -v ~/HostPath:/ContainerPath \
  --name mycontainer \
  <image_name>
🔹 10. Ollama (LLM in Docker)
docker pull ollama/ollama

docker run -d --name ollama -p 11434:11434 ollama/ollama

Enter container:

docker exec -it ollama bash

Run model:

ollama run gemma3:270m
🔹 11. Docker Networking

Create network:

docker network create ai

List networks:

docker network ls

Run containers in network:

docker run -d --name jupylab \
  -p 8888:8888 \
  --network ai \
  jupyter/base-notebook

docker run -d --name ollama \
  -p 11434:11434 \
  --network ai \
  ollama/ollama
🔹 12. FastAPI Run
uv run app.py
🔹 13. GitHub Actions
name: CI Pipeline
on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v5
      - run: echo "CI/CD running"
🔹 14. Hugging Face Upload
git lfs install
git add .
git commit -m "Upload model"
git push