# core/bft-api-doc



## Getting Started

Download links:

SSH clone URL: ssh://git@git.jetbrains.space/siwa/core/bft-api-doc.git

HTTPS clone URL: https://git.jetbrains.space/siwa/core/bft-api-doc.git



These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites

What things you need to install the software and how to install them.

1. Donwload and Install Node.js

```
https://nodejs.org/en/download
```
2. Confirm the installation successful

```
node --version
```
3. Install Redocly CLI using yarn/npm

```
yarn global add @redocly/cli
```
4. Confirm the installation successful

```
redocly --version
```
5. Go to this link and click on /q/openapi

```
https://app.test.briix.com/q/swagger-ui/
```
6. Change extension file into .yaml
7. Build the HTML file using .yaml file

```
redocly build-docs openapi.yaml
```

## Deployment

Add additional notes about how to deploy this on a production system.

## Resources

Add links to external resources for this project, such as CI server, bug tracker, etc.
