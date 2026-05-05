## 👋 Welcome to grafana 🚀

Multi-platform analytics and interactive visualization

## 📋 Description

Multi-platform analytics and interactive visualization

## 🚀 Services

- **app**: grafana/grafana:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/grafana/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/grafana" ~/.local/srv/docker/grafana
cd ~/.local/srv/docker/grafana
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install grafana
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
APP_ADMIN_USER=admin
APP_ADMIN_PASS=changeme_admin_password
APP_SECRET_KEY=changeme_secret_key
EMAIL_SERVER_HOST=172.17.0.1
EMAIL_SERVER_MAIL_FROM=grafana@${BASE_DOMAIN_NAME:-${BASE_HOST_NAME
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:3000

## 📂 Volumes

- `./volumes/data/grafana` - Data storage

## 🔐 Security

- Change all default passwords before deploying to production
- Use strong secrets for all authentication tokens
- Configure HTTPS using a reverse proxy (nginx, traefik, caddy)
- Regularly update Docker images for security patches
- Backup your data regularly

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
