# algorand smart-contract

## Overview

The goal of this project is to create end-to-end Web3 dapps on the Algorand Blockchain to help 10 Academy generate and distribute Non-Fungible Tokens (NFTs) as certificates for trainees who complete a weekly challenge.

### Prerequisites

Make sure you have already installed Docker Engine.
You don’t need to install Nginx or NPM, as both are provided by Docker images.

```
$ docker -v
Docker version 18.03.1-ce, build 9ee9f40
```

### Installing

```
git clone https://github.com/Melak2017/Algorand-smart-contract
cd docker-reactjs
docker build -t docker-reactjs .
docker run -p 80:80 docker-reactjs

```

## Built With

- [React.js](https://reactjs.org/) - The front-end framework used
- [Docker](https://www.docker.com/) - Containerization
- [Materialize](https://materializecss.com/) - Front-end framework

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
