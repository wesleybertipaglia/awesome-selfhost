# 🚀 Awesome Selfhost

A collection of Docker Compose configurations for popular self-hosted applications. This repository makes it easy to deploy and manage your favorite services on your own server, using Docker containers with ready-to-use setups.

## 📚 Table of Contents

* [About](#about)
* [Categories](#categories)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [License](#license)

## 📖 About

The purpose of this project is to showcase alternatives to common daily-use applications for home or work that can be self-hosted. These options are either free or more affordable than their commercial counterparts. Additionally, this repository provides Docker Compose templates and environment variable configurations to simplify the setup and deployment of these applications.

## 📂 Categories

* **[CMS](./src/services/cms)**: Content Management Systems such as WordPress or Ghost
* **[Databases](./src/services/databases)**: Various database systems for data storage and management
* **[Design](./src/services/design)**: Tools for design and creativity workflows
* **[Development](./src/services/dev)**: Services to aid software development and testing
* **[General](./src/services/general)**: Miscellaneous utilities and applications
* **[Infrastructure](./src/services/infra)**: Tools to manage and monitor infrastructure
* **[Media](./src/services/media)**: Applications related to media streaming, management, and editing
* **[Productivity](./src/services/productivity)**: Apps to boost productivity and organization
* **[Security](./src/services/security)**: Tools focused on enhancing security and privacy

Explore the respective folders to find service configurations tailored to each category.

## 🛠️ Getting Started

1. Clone this repository:

```bash
git clone https://github.com/wesleybertipaglia/awesome-selfhost.git
cd awesome-selfhost
```

2. Copy `.env.example` to `.env` and adjust environment variables as needed.

3. Navigate to the desired service directory and launch the stack:

```bash
docker-compose up -d
```

4. Access the service via `localhost` or your server’s IP on the configured port.

5. To stop and remove the containers:

```bash
docker-compose down
```

## 🤝 Contributing

Contributions are very welcome! To add a new service or improve existing configurations:

1. Fork this repository.
2. Create a new branch for your feature: `git checkout -b my-feature`
3. Make your changes with clear commits.
4. Push to your fork and open a pull request.

Please keep contributions consistent with the project style and documentation standards.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
