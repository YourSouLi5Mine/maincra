# Minecraft Crack House

## Installation

1. Install Java8 via: `brew tap adoptopenjdk/openjdk` and `brew cask install adoptopenjdk8`
1. Start the server with `java -Xmx4G -Xms4G -jar server.jar nogui` You can use MB instead of G. ms means the RAM usage when starting the server and mx the RAM used afterwards. You can avoid using `nogui` if you want to see the graphs.
1. In order to invite friends you have to open the TCP/UDP 25556 ports in the modem and provide your ip via `ifconfig | grep 192`
1. Start the `launcher.jar` and inside the Multiplayer option click on `Add new server`. Write the `ip:port` (E.G. `192.168.0.11:25565`)
