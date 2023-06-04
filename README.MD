# Auth-Service

## Description

Authentication micro-service

- Node.js
- Express
- MongoDB with mongoose
- Typescript

## Installation

```md
cd auth  
npm install
```

## Usage

Update yaml files to point to your unique image identifers (I use jsquarem).
Ensure Docker, Kubernetes, and Skaffold are installed and running then execute
the following command to deploy kubernetes cluster from the project root:

```md
skaffold dev
```

## Testing

```md
cd auth  
npm run test
```
