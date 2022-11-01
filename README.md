# ArchitectureSoftware_Lab3

## Installation

- Clone the repository

```bash
git clone https://github.com/Er4ik/dockerising_nodejs_app.git
```

- Install deps in the ./js-devops-dockerising

```bash
npm i
```

## Usage

- If you have node and npm on your pc:

```bash
npm run start:js
```

- If you do not have node and npm on your pc:

```bash
cd js-devops-dockerising
docker build -f Dockerfile -t js:1 .
docker run --rm -it -p 5001:3000 lab3:01
```

App running on Port 80
