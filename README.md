<h1 align="center">Welcome to Load Balancing Algorithms Studies 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-v0-blue.svg?cacheSeconds=2592000" />
  <a href="/" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/fidelissauro" target="_blank">
    <img alt="Twitter: fidelissauro" src="https://img.shields.io/twitter/follow/fidelissauro.svg?style=social" />
  </a>
</p>

> Repository for my load balancing algorithms and comparisons between most commons Load Balancers

### 🏠 [Homepage](/)

### ✨ [Nginx](https://docs.nginx.com/nginx/admin-guide/load-balancer/http-load-balancer/)

* [Nginx - Round Robin (Default)](./nginx/round_robin)
* [Nginx - Weighted Round Robin](./nginx/round_robin_weight)
* [Nginx - Least Connection](./nginx/least_connection)
* [Nginx - Weighted Least Connection](./nginx/least_connection_weight)
* [Nginx - IP Hash (Sticky Session)](./nginx/ip_hash)


## Install

```sh
cd {webserver}/{algorithm}
docker-compose up --force-recreate
```

## Usage

```sh
while true; do curl 0.0.0.0:8080/version ; echo ; done
```


## Author

👤 **Matheus Fidelis**

* Website: https://raj.ninja
* Twitter: [@fidelissauro](https://twitter.com/fidelissauro)
* Github: [@msfidelis](https://github.com/msfidelis)
* LinkedIn: [@msfidelis](https://linkedin.com/in/msfidelis)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](/issues). 

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Matheus Fidelis](https://github.com/msfidelis).<br />
This project is [MIT](LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_