# Lalavent REST API

[![Release Version](https://img.shields.io/badge/release-v.1.0-blue)](https://github.com/algol007/lalavent.server/releases/tag/1.0) [![Node JS](https://img.shields.io/badge/Dependencies-Express%20JS-green)](https://nodejs.org/en/)
![GitHub repo size](https://img.shields.io/github/repo-size/algol007/lalavent.server)
![GitHub contributors](https://img.shields.io/github/contributors/algol007/lalavent.server)
![GitHub stars](https://img.shields.io/github/stars/algol007/lalavent.server?style=social)
![GitHub forks](https://img.shields.io/github/forks/algol007/lalavent.server?style=social)

<p align="center">
  <a href="https://nodejs.org/">
    <img src="https://cdn-images-1.medium.com/max/871/1*d2zLEjERsrs1Rzk_95QU9A.png">
  </a>
</p>

## Table of Contents
- [Prerequiste](#prerequiste)
- [Instalation](#installation)
- [Contributing](#contributing)
- [Related Project](#related-project-frontend)
- [Contributors](#contributors)

## Prerequiste
- Node.js - Download and Install [Node.js](https://nodejs.org/en/).
- MySQL - Download and Install [MySQL](https://www.mysql.com/downloads/) - Make sure it's running on the default port.
- Redis - Download and Install [Redis](https://redis.io/)

## Installation
### Clone
```
$ https://github.com/algol007/lalavent.server.git
$ cd lalavent.server
$ npm install
```

### Create Environment Variable
```
$ touch .env
$ nano .env
```

```
PORT = YOUR_PORT
SECRET_KEY = YOUR_SECRET_KEY

EMAIL = YOUR_EMAIL
PASS = YOUR_PASSWORD

DB_USER = YOUR_DB_USERNAME
DB_PASS = YOUR_DB_PASSWORD
DB_NAME = YOUR_DB_NAME

BASE_URL = YOUR_SERVER_URL
CLIENT_URL = YOUR_CLIENT_URL
```

### Start Development Server
```
$ npm run serve
```

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
1. Create your Feature Branch  ```git checkout -b [feature]```
2. Commit your Changes ```git commit -m 'Add some feature'```
3. Push to the Branch ```git push origin [feature]```
4. Open a Pull Request

## Related Project (Frontend)

* [`Frontend-Lalavent`](https://github.com/fblazt/lalavent.client)

## Contributors

<center>
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/ichvanul">
          <img width="150" src="https://avatars1.githubusercontent.com/u/62008205?s=460&u=d23a93172c5e4c40b9b033e273a3359b2742c568&v=4" alt="Ichvanul Yulizar Putra"><br/>
          <b>Ichvanul Yulizar Putra</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/algol007">
          <img width="150" src="https://avatars3.githubusercontent.com/u/13137672?s=460&u=b5226ccdf4cd9c9a8505215b77b2a15d134d92b5&v=4" alt="Ady Rahmansyah"><br/>
          <b>Ady Rahmansyah</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/fblazt">
          <img width="150" src="https://avatars3.githubusercontent.com/u/48191467?s=460&u=c06616d146930100dfb5eb5c4ab10fd00d01ac41&v=4" alt="Firman"><br/>
          <b>Firman</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/shoelfikar">
          <img width="150" src="https://avatars2.githubusercontent.com/u/55390061?s=400&u=74904e4071d513890cfd34031b87977eeddb09b8&v=4" alt="Sulfikardi"><br/>
          <b>Sulfikardi</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/slucter">
          <img width="150" src="https://avatars2.githubusercontent.com/u/61655908?s=460&u=1e1c0b55b30cf502f264038f39609fd6dc8636b8&v=4" alt="Muhamad Irhashdianto"><br/>
          <b>Muhamad Irhashdianto</b>
        </a>
      </td>
    </tr>
  </table>
</center>
