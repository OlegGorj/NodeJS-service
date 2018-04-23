# NodeJS-service

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/54db520cbcb445999203f0513db377f1)](https://app.codacy.com/app/oleggorj/NodeJS-service?utm_source=github.com&utm_medium=referral&utm_content=OlegGorj/NodeJS-service&utm_campaign=badger)

Simple NodeJS application to test deployment of CI/CD pipeline (Docker, Packer, Ansible and Terraform)

## Install Express

```bash
  $ sudo npm install express-generator -g
```

## `NodeJS-service` application deployment and start

Generate stubs for the app NodeJS-service
```bash
  $ express --view=jade NodeJS-service
```

change directory:
```bash
  $ cd NodeJS-service
```

install dependencies:
```bash
  $ npm install
```

run the app:
```bash
  $ DEBUG=nodejs-service:* npm start
```




---
