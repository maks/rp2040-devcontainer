# Dev container for RP2040 (PI Pico) development

Just the minimal deps specified in the Pi Pico C SDK [Getting Started Guide](https://datasheets.raspberrypi.com/pico/getting-started-with-pico.pdf) based on a Debian image.

Need to have devcontainer cli installed:
`npm install -g @devcontainers/cli`

and then to publish:
`devcontainer build --workspace-folder . --push true --image-name ghcr.io/maks/rp2040-devcontainer:latest`

## TODO

* setup Github actions CI builds of for prebuilt container.