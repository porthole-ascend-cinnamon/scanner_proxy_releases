# Пошук проксі для [mhddos_proxy](https://github.com/porthole-ascend-cinnamon/mhddos_proxy_releases)

### Опис

1. Автоматично шукає і перевіряє публічні проксі, та надсилає робочі для використання mhddos_proxy
2. Понад **10 разів** ефективніший за попередню версію
3. Потребує стабільне (бажано провідне) з'єднання - найкращий варіант - виділені сервери
4. Тільки Linux та macOS, обидві через Docker
5. Майте на увазі - ви можете покласти свою мережу, якщо вона слабка, або отримати звіт про порушення / бути
   заблокованим у будь-який час
6. Ваш IP буде відкритим - перша фаза сканування обходить VPN, навіть якщо він увімкнений

### Використання

1. Встановіть і запустіть [Docker](https://docs.docker.com/desktop/#download-and-install)
2. Виконайте команду (замініть `-it` на `-d` для запуску у фоновому режимі)

`docker run -it --rm --pull always --net=host ghcr.io/porthole-ascend-cinnamon/scanner_proxy`

# Proxy scanner for [mhddos_proxy](https://github.com/porthole-ascend-cinnamon/mhddos_proxy_releases)

### Description

1. Automatically searches and verifies public proxies, then send the working ones to be used by mhddos_proxy
2. Over **10 times** more efficient then previous version
3. Requires stable (preferably wired) connection - dedicated server is the best option
4. Only Linux and macOS, both via Docker
5. Beware - you can down your network if it's weak, and receive abuse report / get blocked at any time
6. Your IP will be exposed - the first phase of the scan bypasses the VPN, even if it is enabled

### Usage

1. Install and launch [Docker](https://docs.docker.com/desktop/#download-and-install)
2. Run the command (swap `-it` for `-d` to launch in the background)

`docker run -it --rm --pull always --net=host ghcr.io/porthole-ascend-cinnamon/scanner_proxy`
