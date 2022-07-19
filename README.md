# Proxy scanner for [mhddos_proxy](https://github.com/porthole-ascend-cinnamon/mhddos_proxy_releases)

### Опис

1. Понад **20 разів** ефективніший за попередню версію
2. Потребує стабільне (бажано провідне) з'єднання - найкращий варіант - виділені сервери
3. Тільки Linux та macOS, обидві через Docker
4. Майте на увазі - ви можете вимкнути свою мережу, якщо вона слабка, і отримати звіт про порушення / бути
   заблокованим у будь-який час
5. Ваш IP буде відкритим - перша фаза сканування обходить VPN, навіть якщо він увімкнений

### Використання

1. Встановіть і запустіть [Docker](https://docs.docker.com/desktop/#download-and-install)
2. Виконайте команду (для запуску у фоновому режимі замініть `-it` на `-d`)

`docker run -it --rm --pull always --net=host ghcr.io/porthole-ascend-cinnamon/scanner_proxy`

### Description

1. Over **20 times** more efficient then previous version
2. Requires stable (preferably wired) connection - dedicated server is the best option
3. Only Linux and macOS, both via Docker
4. Beware - you can down your network if it's weak, and receive abuse report / get blocked at any time
5. Your IP will be exposed - the first phase of the scan bypasses the VPN, even if it is enabled

### Usage

1. Install and launch [Docker](https://docs.docker.com/desktop/#download-and-install)
2. Run the command (to launch in the background, swap `-it` for `-d`)

`docker run -it --rm --pull always --net=host ghcr.io/porthole-ascend-cinnamon/scanner_proxy`
