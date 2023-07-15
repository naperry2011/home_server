# Home Server with Docker and Plex

![Docker Logo](https://www.docker.com/sites/default/files/d8/2019-07/horizontal-logo-monochromatic-white.png)
![Plex Logo](https://plex.tv/web/app/images/plex-invite-logo.png)

Welcome to my Home Server setup! In this repository, I'll document how I use Docker containers to host Plex, a popular media server application, and utilize other tools to enhance my setup.

## Table of Contents

- [About Docker and Plex](#about-docker-and-plex)
- [Docker Compose](#docker-compose)
- [Portainer for Container Monitoring](#portainer-for-container-monitoring)
- [MkDocs for Documentation](#mkdocs-for-documentation)
- [Configuration](#configuration)
- [Adding Media](#adding-media)
- [Accessing Plex](#accessing-plex)
- [Contributions](#contributions)
- [Contact](#contact)

## About Docker and Plex

[Docker](https://www.docker.com/) is a platform that allows you to create, deploy, and run applications in isolated containers. It offers a flexible and consistent environment, making it easy to manage applications and their dependencies.

[Plex](https://www.plex.tv/) is a media server application that organizes your multimedia content (movies, TV shows, music, etc.) and provides a user-friendly interface to access and stream media across devices.

Using Docker to host Plex ensures a clean separation of the application from the host system and simplifies updates and maintenance.

## Docker Compose

The `docker-compose.yml` file in this repository defines the Docker services and configurations required to run Plex as a container. Docker Compose allows us to manage multiple containers as a single application.

## Portainer for Container Monitoring

[Portainer](https://www.portainer.io/) is a user-friendly management tool for Docker. I use Portainer to monitor and manage my Docker containers. With Portainer's web interface, I can easily view container status, logs, and resource usage.

## MkDocs for Documentation

[MkDocs](https://www.mkdocs.org/) is a static site generator that allows us to create beautiful and easy-to-maintain documentation. I use MkDocs to document the steps and configuration details of my Home Server setup, making it simple to refer back to the setup process and any customization.

## Configuration

Before running Plex, make sure to configure the `docker-compose.yml` file with your desired settings, such as the media library location, port mappings, and timezone. You can also customize other Plex settings, such as remote access and library directories, as needed.

## Adding Media

To add media to Plex, simply place your media files (movies, TV shows, music, etc.) in the configured media library location. Plex will automatically scan and organize your media into a user-friendly library.

## Accessing Plex

Once the Docker containers are up and running, you can access Plex by opening a web browser and navigating to the configured Plex URL (e.g., http://localhost:32400).

## Contributions

I welcome feedback, suggestions, and contributions to this repository. If you encounter any issues, have ideas for improvement, or want to share additional setup instructions, feel free to open an issue or submit a pull request.

## Contact

You can reach me via email at your.email@example.com or connect with me on [LinkedIn](https://www.linkedin.com/in/your-linkedin-profile).

Enjoy your Plex media server, Portainer container monitoring, and MkDocs documentation! 🎥📊📚
