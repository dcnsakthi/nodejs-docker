# nodejs-docker
nodejs-docker Learning Repo (todo app on NodeJS).

**Step1:** Clone Repo. Modify if required.

**Step2:** Build Docker Image. `docker build -t dcnsakthi/todo:latest .`

**Step3:** Push Docker Image to DockerHub. `docker push dcnsakthi/todo:latest`

**Step4:** Pull Docker Image to Locally. `docker pull dcnsakthi/todo:latest` Or Run Docker Container. `docker run -dp 3088:3000 dcnsakthi/todo:latest`

**Step5:** Browse through the URL. `http://localhost:3088/`
