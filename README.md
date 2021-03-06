# ![eun][logo]

[![npm][npm-badge]][npm][![Build Status][build-badge]][build-status] [![Standard code style][standard-badge]][standard] [![License][license-badge]][license]

* **automatically** logs **expenses** by **monitoring** mail
* provides weekly and monthly **cash flow** of expenses and income
* **authentication** using a secret key (uses Storage API to store token locally)

![Screenshot 1](./docs/Screenshot-1.png) ![Screenshot 2](./docs/Screenshot-2.png) ![Screenshot 3](./docs/Screenshot-3.png)

## Installation

Available on [npm][]

### Node

```bash
git clone https://github.com/omarchehab98/eun
cd eun
npm install
npm test
npm run build
npm start
```

### Docker

```bash
git clone https://github.com/omarchehab98/eun
cd eun
docker-compose up
```

* `npm run dev-client`
Watches the client directory, keeps browser in sync with new changes.

* `npm run dev-server`
Watches the server directory, restarts server when changes are made.

* `npm run lint`
Code quality.


## License

[MIT][license] © [Omar Chehab][author]

<!-- Definitions -->

[logo]: https://cdn.rawgit.com/omarchehab98/eun/312f622f/logo.svg

[build-badge]: https://travis-ci.org/omarchehab98/eun.svg?branch=master

[build-status]: https://travis-ci.org/omarchehab98/eun

[standard]: http://standardjs.com

[standard-badge]: https://img.shields.io/badge/code_style-standard-brightgreen.svg

[license-badge]: https://img.shields.io/github/license/omarchehab98/eun.svg

[license]: https://github.com/omarchehab98/eun/blob/master/LICENSE

[author]: https://omarchehab.com

[npm]: https://www.npmjs.com/package/eun

[npm-badge]: https://img.shields.io/npm/v/eun.svg
