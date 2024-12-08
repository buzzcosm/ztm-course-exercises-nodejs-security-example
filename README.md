# Security Example

`ZTM` Udemy Course - [Complete NodeJS Developer](https://www.udemy.com/course/complete-nodejs-developer-zero-to-mastery).

## Prerequisite

- `Node.js` is installed ⚡
- Prefered Code-Editor/IDE is installed (For example: `vscode`) ✍
- Terminal is ready 😎

Origin source on GitHub [here](https://github.com/odziem/security-example).

## Description

Exercises for Security Example.

## Open SSL

Creaate:

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
- [helmet.js](https://helmetjs.github.io/) 🔐🛡️⚡💡🔥
  - My Docs: [helmet.md](./docs/helmet.md)
- get free ca-signed certificate
  - [Let's Encrypt](https://letsencrypt.org/)
  - [ZeroSSL](https://zerossl.com/)
  - [SSL For Free](https://www.sslforfree.com/)
- Security
  - [Cross-Site Scripting (XSS)](https://www.blackduck.com/glossary/what-is-cross-site-scripting.html#:~:text=Definition,the%20user%20to%20click%20it.)
  - [okta - article: authentication vs authorization](https://www.okta.com/identity-101/authentication-vs-authorization/#:~:text=Authentication%20confirms%20that%20users%20are,and%20access%20management%20(IAM).)