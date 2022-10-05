A better sample here, https://github.com/tmtk75/prisma-trpc-chakra-nextjs-boilerplate

# Create T3 App + aws-sdk v3 + Dockerfile
This repository was generated with `yarn create t3-app`.
Then a Dockerfile and aws-sdk v3 were added as a sample.


# Getting Started to work
Just try the below commands, then open <http://localhsot:3000>.
```
[0]$ docker compose up localstack postgres
...

[1]$ yarn
...

[1]$ AWS_ENDPOINT=http://localhost:4566 yarn dev
...
ready - started server on 0.0.0.0:3000, url: http://localhost:3000
...
```
Next.js dev-server starts using postgresql and s3@localstack served by docker-compose.


# Build docker image
```
$ docker build -t t3-app .
...

$ docker run t3-app
```
TBD

