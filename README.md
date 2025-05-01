# .github

## ☁️ Server

- **Provider:** [DigitalOcean](https://www.digitalocean.com/)
- **Droplet Specs:**
  - Ubuntu 22.04
  - 4 vCPUs
  - 8 GB RAM
  - 120 GB SSD
- **Access:**
  - via SSH
    ```bash
    ssh -i ~/.ssh/YOUR_KEY_NAME root@YOUR_SERVER_IP
    ```

## 🌐 Domain

- **Registrar / DNS Provider:** [Amen.pt](https://controlpanel.amen.pt/)
- **Domain:** `lupa-digital.pt`
- **DNS Setup:**
  - A-record pointing to the droplet IP