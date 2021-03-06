# Templates

This folder contains some building blocks.

## ANSIBLE

| Role              | Description |
| ----              | ----------- |
| `docker`          | Install docker      |
| `golang`          | Install golang      |
| `kali-cloud`      | Install tools to perform cloud assessments (AWS, Azure, GCP) |
| `kali-metasploit` | 3. Install MSF, configure Postgres, setup msfdb and Armitage |
| `kali-os`         | 1. Update OS, setup locales, add users, config ufw and zsh |
| `kali-red`        | For red teams (empire, dnscat2, etc.). **UNDER DEVELOPMENT** |
| `kali-sw`         | 2. Install basic maintenance, dev, and pt tools |
| `kali-wifi`       | Wi-Fi pentesting tools     |
| `mobile-android`  | Android tools              |
| `mobile-ios`      | iOS tools                  |
| `nginx`           | Fully configured nginx     |
| `sublimetext`     | Install sublimetext        |


## DOCKER

| Folder                            | Description |
| --------------------------------- | ----------- |
| `docker_ansible_worker`           | Image for Ansible. Published on [Docker Hub](https://cloud.docker.com/u/marcolancini/repository/list) |
| `docker_compose_clair`            | Spin up `Clair`, alongside `Postgres` and `Klar`, to scan Docker images for security vulnerabilities |
| `docker_compose_django`           | Django setup with `Postgres` (database), `Redis` (cache), and `nginx` (proxy) |
| `docker_compose_flask`            | Flask setup  |
| `docker_compose_nginx-proxy`      | Nginx-proxy setup |
| `docker_compose_wekan-bookstack`  | Local setup for Wekan and Bookstack |
| `docker_go_dev`                   | Development image for Golang. Published on [Docker Hub](https://cloud.docker.com/u/marcolancini/repository/list)  |
| `docker_kali`                     | Image for kali. Published on [Docker Hub](https://cloud.docker.com/u/marcolancini/repository/list) |
| `docker_nomad`                    | Image for Nomad. Published on [Docker Hub](https://cloud.docker.com/u/marcolancini/repository/list)  |
| `docker_python_dev`               | Development image for Python2/3. Published on [Docker Hub](https://cloud.docker.com/u/marcolancini/repository/list) |
| `docker_vault`                    | [Docker + Consul + Vault](https://github.com/marco-lancini/docker_vault) |



## TERRAFORM

| Folder                            | Description |
| --------------------------------- | ----------- |
| `terraform_vpc`                   | Terraform template for a full VPC setup |
