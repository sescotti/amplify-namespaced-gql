ARG VARIANT="20-bullseye"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:1-${VARIANT}

ARG AMPLIFY_VERSION=${AMPLIFY_VERSION}

RUN npm install -g @aws-amplify/cli@${AMPLIFY_VERSION}

USER node
# Downloads amplify binary
RUN amplify
# RUN amplify add codegen

USER root