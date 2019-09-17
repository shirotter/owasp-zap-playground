# owasp-zap-playground

[OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project#tab=Main) playground with [WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project)

## Prerequisites for use

The following must be installed and available.

- Docker

## Usage

### 1. Clone a repository

Clone a repository and change directory.

```bash
git clone https://github.com/shirotter/owasp-zap-playground.git && cd $(basename $_ .git)
```

### 2. Run containers

Builds, creates, starts, and attaches to containers for services in the background.

```bash
docker-compose up -d
```

### 3. Access to WebGoat

Once started containes.

1. Access to [http://localhost:8080/WebGoat](http://localhost:8080/WebGoat)
1. Register new user and signin.

