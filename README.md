[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <p align="center"><img src="./docs/images/logo.png" width="26" /></p>
  <p align="center" style="color: #666;">A simple time tracking application</p>
</p>

## What's Hackaru?
Hackaru is the simple time tracking application.
> Hackaru (測る) means "Measure" in Japanese.

## Screens

<img src="./docs/images/calendar.png" width="500" />
<img src="./docs/images/reports.png" width="500" />

## Features

- [PWA](https://developers.google.com/web/progressive-web-apps/) support. You can use on iOS and Android.
- OAuth 2.0 provider support.
- Open source. You can build on your server.

## How to use?
You can use Hackaru on the official website. It's free.
- https://www.hackaru.app

## Use Docker
You can try Hackaru on your local in development mode using [docker-compose](https://docs.docker.com/compose/install).  
Run below commands and access http://localhost:3333.

```
git clone https://github.com/hackaru-app/hackaru.git && \
cd ./hackaru && \
cp .env.api.sample .env.api && \
cp .env.web.sample .env.web && \
docker-compose run --rm api bin/rails db:setup && \
docker-compose up
```

## Repos
- [hackaru-app/hackaru-web](https://github.com/hackaru-app/hackaru-web)
- [hackaru-app/hackaru-api](https://github.com/hackaru-app/hackaru-api)
- [hackaru-app/hackaru-desktop](https://github.com/hackaru-app/hackaru-desktop)
- [hackaru-app/hackaru-official](https://github.com/hackaru-app/hackaru-official)

## License
- [MIT](./LICENSE)

## Donation
<a href="https://www.buymeacoffee.com/T4KDHBPV6" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
