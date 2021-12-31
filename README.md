## Apply for Radxa CM3

Radxa is donating some free [ROCK3 computing modules](https://wiki.radxa.com/Rock3/CM3) to open source hardware projects.

## How to apply

Send a new PR to this repository on GitHub, append your application table(sort Project Name). Radxa team will review/ask questions/discuss about the project detail. If the project is interesting or welcomed by the community, we will approve it. Radxa Team will contact the developer for the further sample shipping&development etc.

## CM3 projects list:

| Project Name        | CM3 Model     | Hardware(Carrier Board)                                      | Software                                                | Notes                                                        |
| ------------------- | ------------- | ------------------------------------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------ |
| AI-Speaker          | RM116-D8E\*   | Custom design                                                | [AI Speaker](https://ai-speaker.com/docs/ais_app_index) | We would like to release something like Home Assistant Amber dev board with Radxa CM3 |
| Buildroot           | RM116-D1E0    | Radxa E23                                                    | [Buildroot](https://buildroot.org/)                     | Adding CM3 support for buildroot                             |
| currypi             | RM116-D8E\*   | [CurryPi](https://github.com/devguardio/currypi)             | Linux                                                   | [Pictures](https://twitter.com/arvidep/status/1445363759313297412) |
| Device Farm         | Any           | Any                                                          | [Device Farm](https://github.com/device-farm)           | DEVICE.FARM is a platform to deploy containerized services to IoT devices, similar to Balena. We need the board for testing before we publish them as supported. |
| K3s ARM cluster     | RM116-D8E8    | 6 x Rpi CM4                                                  | Ubuntu                                                  | Testing Kubernetes on AArch64 micro clusters                 |
| MSLA resin printers | RM116-D4E32W  | Currently the RPi CM4 + LCD                                  | Raspbian/Linux                                          | The project is currently in experimental state, I am working on Linux driver for current state-of-the-art LCDs featured on resin printers. However, these LCDs use 2x 4-lane MIPI interface, thus I am experimenting with multiplexing MIPI on Rpi CM4 (which sucks). This is why I am reaching out to you - as ROCK3 features 2x 4-lane MIPI! This is a killer feature for such a project. Just to give you context; the resin 3D printing is extremely limited a dominated by Chitusystems. They have terrible closed ecosystem, unlike the open ecosystem available for FDM printers. It is really hard for open project to start, as there is a big obstacle in driving high-resolution LCDs required for these printers. |
| NixOS               | RM116-D4E32W  | Radxa E23                                                    | NixOS                                                   | -                                                            |
| OpenWRT             | RM116-D1E0    | Radxa E23                                                    | [OpenWRT](https://openwrt.org/)                         | I would like to port Openwrt on CM3 + Radxa E23 carrier board |
| Piunora             | Any with WiFi | [Piunora Pro](https://www.crowdsupply.com/diodes-delight/piunora) | Linux                                                   | For compatability testing and new hardware designs           |
| sataPi              | Any model     | Custom PCB design WIP                                        | Debian                                                  | sataPi is a project that aims to fill the empty sata bay slots from a pc case with computing power. Since it is inside a pc, the power will be delivered trough standard conectors in pcs like molex or sata power. Project will be fully opensource, and maybe there will be a kickstarter campaign for it. |
| -                   | RM116-D4E32W  | Currently the RPi CM4 + LCD                                  | Raspbian/Linux                                          | Project will be open sourced closer to going on sale, currently it's not public, details and photos can be shared privately. There is some tease photos [here](https://twitter.com/arturo182/status/1364003299083624452). |

