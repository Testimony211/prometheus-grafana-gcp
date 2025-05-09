# Prometheus & Grafana Monitoring Stack on GCP

This project demonstrates the deployment of a basic monitoring stack using Prometheus, Grafana, and Node Exporter on the Google Cloud Platform (GCP). It includes steps to set up a GCP VM, install Docker, and run monitoring tools using Docker Compose.

---

## 🚀 Project Overview

- **Prometheus** is used to collect metrics.
- **Node Exporter** exposes system-level metrics.
- **Grafana** visualises metrics through dashboards.
- **Google Cloud Platform (GCP)** hosts the monitoring stack.

---

## 📦 Technologies Used

- Google Cloud Platform (GCP)
- Docker & Docker Compose
- Prometheus
- Grafana
- Node Exporter
- Ubuntu (on GCP Compute Engine VM)

---

## 🛠️ Setup Instructions

### 1. Create a VM on GCP

- Use an **e2-micro** VM (Free Tier)
- Ubuntu 22.04 LTS
- Allow HTTP and HTTPS traffic
- Note the external IP

### 2. SSH into the VM

Use the SSH button in the GCP Console to access your VM terminal.

### 3. Install Docker & Docker Compose

```bash
sudo apt update
sudo apt install docker.io docker-compose -y
sudo usermod -aG docker $USER
newgrp docker


### 4. Create a VM on GCP

- Use an **e2-micro** VM (Free Tier)
- Ubuntu 22.04 LTS
- Allow HTTP and HTTPS traffic
- Note the external IP

