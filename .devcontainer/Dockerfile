ARG _DEV_CONTAINERS_BASE_IMAGE=placeholder
ARG VARIANT="20-bullseye"
FROM mcr.microsoft.com/devcontainers/typescript-node:1-${VARIANT} AS dev_container_auto_added_stage_label

RUN su node -c "npm install -g bun"

