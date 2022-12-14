# Articles app with nhost

Aim of this project: explain the tool nhost.

Nhost is an open source Firebase alternative with graphql.

## Prerequisite

- Graphql
- React
- Typescript

## Architecture

On the backend, just nhost :p

On frontend, reactjs with typescript, chakra, react_router_dom, appolo client for graphql, codegen for generation of graphql hooks

## Software need

- Docker
- nodejs
- Git

## The project

After signin/signup, user can add articles on the platform. The user can add like to favorite article.

## Installation of the project

First, install nhost cli

```
sudo curl -L https://raw.githubusercontent.com/nhost/cli/main/get.sh | bash
After cloning, you have to install node_modules with the command
```

Then, install node modules dependencies with pnpm

> pnpm install

Then rename .env.development to .env in frontend/ and backend/functions/

## Launch the project

To launch the frontend

```
cd frontend/;
pnpm dev;
```

To launch the backend

```
cd backend/;
nhost up;
```

You can see containers in your docker environnement

## Commands

In frontend and backend/functions, you can use graphql-codegen to compute custom graphql hooks :

```
pnpm run codegen;
```
