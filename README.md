# python-docker-dev-template
Template for the development of Python codebase in Docker

# Steps for environment creation

1. Build docker container
```bash
sudo docker-compose build .
```

2.1 Start docker container development environment for CLI development
```bash
sudo docker-compose run code bash
```

2.2 Start jupyter notebook
```
sudo docker-compose up --build
```

# Add a python package

1. Start the container in interactive mode
```
sudo docker-compose run code bash
```

2. Install/Add package using poetry
```
poetry add <package-name>
```
