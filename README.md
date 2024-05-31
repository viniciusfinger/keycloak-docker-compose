# Docker-compose template for Keycloak 🔑

This docker-compose template sets up a Keycloak server, which is an open-source identity and access management solution. Keycloak provides features such as single sign-on (SSO), user federation, identity brokering, and social login. This template simplifies the deployment and configuration process, making it easy to get started with Keycloak for securing your applications and services.

![](logo.jpeg)

## Prerequisites

Before running the application, ensure you have the following installed:

- Windows WSL (Only if you're on Windows)
- Docker 🐳

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/viniciusfinger/keycloak-docker-compose.git
   ```

2. Run the compose:

   ```bash
   docker-compose up
   ```

## Usage

1. After running the container, go to the Keycloak admin panel at:
[localhost:7080](localhost:7080) or the port you defined at docker-compose.

2. Login with user `admin` and password `admin` or the user and pass you defined at docker-compose.
3. All done!

## Customization

Feel free to clone and customize the file to suit your needs.