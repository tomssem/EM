# EM
Electronics and microcontollers course for M21

## Dev environment:
### Docker container
Developed in a Docker container, can be run by doing:
`docker run --rm  -it -w /app -v ~/.gitconfig:/etc/gitconfig -v $(pwd):/app -v ~/.ssh:/tmp/.ssh:ro --device=/dev/ttyACM0 tfwnicholson/platformio`
### PlatformIO configuration
Setup using command:
`pio project init --ide vim --board megaatmega2560`
## Developing
Once set up,

You can use the command
``pio run --target upload``
To upload to the device

