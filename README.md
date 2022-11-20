# OWASP Juice Shop

OWASP Juice Shop is probably the most modern and sophisticated insecure web application! It can be used in security trainings, awareness demos, CTFs and as a guinea pig for security tools! Juice Shop encompasses vulnerabilities from the entire [OWASP Top Ten](https://owasp.org/www-project-top-ten) along with many other security flaws found in real-world applications!

# Requirements

- [Docker Engine](https://www.docker.com)
- [Docker Compose](https://docs.docker.com/compose/install/)

# Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dockfiles/OWASP-Juice-Shop.git owasp-juice-shop
```

cd into the new directory

```bash
cd owasp-juice-shop
```

### 2. Run the OWASP Juice Shop container

```bash
docker compose up -d
```

### 3. Ready to go!

Visit `http://localhost:3000` in your web browser
