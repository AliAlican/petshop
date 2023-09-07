# 🐾 PetShop Application

## Overview

Welcome to the **PetShop** application! This guide will help you with the installation and setup process. The app runs within a Docker container for easy deployment and seamless management.

## 📝 Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Accessing the Application Container](#accessing-the-application-container)
- [Database Configuration](#database-configuration)

---

## 🔐 Prerequisites

Before you proceed, make sure you have the following software installed:

- Docker
- Docker Compose

If you don't have these prerequisites installed, please follow the installation guide for your specific operating system.

---

## ⚙️ Installation

To get the **PetShop** application up and running, follow these simple steps:

1. **Clone the repository or download the code to your local machine.**

2. **Open your terminal and navigate to the directory containing the `docker-compose.yml` file.**

3. **Run the following command to start the services in detached mode:**

    ```bash
    docker-compose up -d
    ```

---

## 📟 Accessing the Application Container

For more advanced tasks or debugging, you can access the application container directly:

```bash
docker exec -it app-petshop bash
