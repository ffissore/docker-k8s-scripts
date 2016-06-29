# docker-k8s-scripts

A collection of scripts that ease daily docker and kubernetes usage.

  - `docker-multitail CONTAINER_NAME [CONTAINER_NAME ...]`: shows multiple container logs in one terminal window (requires `multitail`)
  - `k8s-multitail POD_NAME [POD_NAME ...]`: just like `docker-multitail` but for k8s pods
  - `docker-remove-unused-images`: removes images marked as `dangling`
  - `docker-remove-unused-volumes`: removes volumes marked as `dangling`
  - `docker-stop-all`: stops all running containers
  - `docker-stop-remove CONTAINER_NAME [CONTAINER_NAME ...]`: stops and remove container(s)

## Usage

Clone the repo somewhere on your disk, than add that folder to your `PATH` environment variable.

## Licenses

Each script has its own license. When not specified, a link to the original source of the code is provided.
Everything brand new is released under GPLv3

