# Jenkins (for Raspberry Pi)

Docker image configuration for [Jenkins](https://jenkins.io/) working on [Raspberry Pi 3](https://www.raspberrypi.org/).

## Getting started

### Prerequisites

* Docker

### Building the image

Build the image with the command
```
docker build --tag jenkins-rpi .
```

### Usage

Use the image as a base for other images, or run Jenkins directly in Docker with the command
```
docker run --rm jenkins-rpi
```
