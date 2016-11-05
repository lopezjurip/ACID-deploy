# Deploy

Install Docker and Docker-compose.

Setup environment variables:

> Create an account on SendGrid to send emails: https://sendgrid.com

```sh
export SECRET_KEY_BASE=SECRET_KEY_BASE
export EMAIL_USERNAME=username
export EMAIL_PASSWORD=password
export EMAIL_DOMAIN=sender.mydomain.com
```

Run or update current running containers with:

```sh
docker-compose up -d --build
```

To stop and/or remove them:

```sh
docker-compose stop
docker-compose rm
```
