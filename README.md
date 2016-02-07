## About

This repo contains a super-simple way to create an rboot_config structure for [rBoot](https://github.com/raburton/rboot) to be flashed to an ESP8266. The checksum byte is not supported. *Do note that ROM addresses are little-endian.*

## Usage

1. Modify `source.txt` to suit your needs
2. Execute `gen.sh`
3. Flash the newly created `rconfig.bin` to the ESP8266 (default location is 0x1000)
