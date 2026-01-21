## 👋 Welcome to grafana 🚀

Grafana - Analytics & monitoring dashboards

## 📋 Description

Grafana is the open-source platform for monitoring and observability. Visualize metrics, logs, and traces from multiple sources.

## 🚀 Services

- **app**: Grafana (`grafana/grafana:latest`)

## 📦 Installation

```shell
composemgr install grafana
```

## 🔧 Configuration

```shell
APP_ADMIN_USER=admin
APP_ADMIN_PASS=changeme_admin_password
APP_SECRET_KEY=changeme_secret_key
```

## 🌐 Access

- **Grafana**: http://localhost:3000
- **Default Login**: admin / changeme_admin_password

## 📂 Volumes

- `./rootfs/data/grafana` - Dashboards and configuration

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
