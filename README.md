# openwrt-builder

build custom openwrt with github actions

## lienol-21.02-luci19

[![openwrt-21.02](https://img.shields.io/github/workflow/status/RookieZoe/openwrt-builder/openwrt-21.02?color=34d058&label=openwrt&logo=github&logoColor=fff)](https://github.com/RookieZoe/openwrt-builder/actions/workflows/openwrt-21.02.yml)
[![rookiezoe/openwrt:latest](https://img.shields.io/docker/v/rookiezoe/openwrt?label=rookiezoe%2Fopenwrt%3Alatest&logo=docker&logoColor=fff)](https://hub.docker.com/r/rookiezoe/openwrt/tags?page=1&ordering=last_updated)

Source Code: [Lienol/openwrt](https://github.com/Lienol/openwrt)

Feeds: ~~[openwrt-21.02.feeds](./openwrt-21.02.feeds)~~ Just change luci version from 21.02 to 19.07 ([code](https://github.com/RookieZoe/openwrt-builder/blob/main/prebuild.bash#L21))

x86_64_with-samba: [openwrt-21.02-x86_64_with-samba.config](./openwrt-21.02-x86_64_with-samba.config) (image only)

x86_64: [openwrt-21.02-x86_64.config](./openwrt-21.02-x86_64.config) (both docker && image)

aarch64: [openwrt-21.02-aarch64.config](./openwrt-21.02-aarch64.config) (both docker && image)

### luci app && package list

见 [wiki](https://github.com/RookieZoe/openwrt-builder/wiki)
