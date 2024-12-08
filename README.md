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
  - My Docs: [Two-Factor Authentication (2FA)](./docs/two-factor-authentication.md)
  - [JWT - JSON Web Tokens Standard](https://jwt.io/)
    > **Warning**: JWTs are credentials, which can grant access to resources. Be careful where you paste them! We do not record tokens, all validation and debugging is done on the client side.
  - [okta: What is OAuth 2.0](https://auth0.com/intro-to-iam/what-is-oauth-2)

## Interesting Stuff

- [BOOMERANG - A simple testing tool to debug your APIs](https://boomerangapi.com/)
- [akamai - mPulse Boomerang](https://techdocs.akamai.com/mpulse-boomerang/docs/welcome-to-mpulse-boomerang)
- [Mozilla: HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [Google Cloud Platform (GCP)](https://cloud.google.com/gcp)
- [Auth for Generative AI Applications](https://www.auth0.ai/)
- [okta: Homepage - Everything starts with Identity](https://www.okta.com/)