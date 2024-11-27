# Security Example

`ZTM` Udemy Course - [Complete NodeJS Developer](https://www.udemy.com/course/complete-nodejs-developer-zero-to-mastery).

## Prerequisite

- `Node.js` is installed ⚡
- Prefered Code-Editor/IDE is installed (For example: `vscode`) ✍
- Terminal is ready 😎

## Description

Exercises for Security Example.

## Open SSL

```shell
openssl req -x509 -newkey rsa:4096 -nodes -keyout key.pem -out cert.pem -days 365
```

## Process

Install npm packages ⬇

```shell
npm install
```

Run node application 🏎️💨

```shell
npm start
```

```shell
npm run dev
```

Clean packages 🧹🪣

```shell
npm run clean
```

Check vulnerabilities 🤔

```shell
npm audit
```

Fix vulnerabilities if needed ✅

```shell
npm audit fix
```

## Useful references

- [wireshark](https://www.wireshark.org/)
- [Let's Encrypt](https://letsencrypt.org/)
- [Wikipedia - Self-signed certificate](https://en.wikipedia.org/wiki/Self-signed_certificate)
- [openssl](https://openssl.org/)
- [helmet.js](https://helmetjs.github.io/)