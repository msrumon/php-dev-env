# PHP Development Environment

This project acts as a sample for working with PHP and Docker. The default `nginx` branch holds the setup for PHP-FPM (FastCGI Process Manager) and nginx (as reverse proxy). The other `apache` branch holds setup for PHP paired with Apache server. In both the branches, the app can be started by running the following command:

```bash
docker compose up --detach app
```
