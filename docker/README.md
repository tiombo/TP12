# Image Docker (Jupyter Notebook)

### Image docker du cours (Docker Hub)
`docker pull mswawola/csfoy-420-a52-sf:latest`

### Exécution sur Linux
`docker run --rm -it -p 8888:8888 -v $(pwd):/notebooks --name <nom_du_conteneur> mswawola/csfoy-420-a52-sf:latest`

### Exécution sur Powershell
`docker run --rm -it -p 8888:8888 -v ${PWD}:/notebooks --name <nom_du_conteneur> mswawola/csfoy-420-a52-sf:latest`

### Création de l'image à partir du Dockerfile
`docker build -t <nom_image> .`