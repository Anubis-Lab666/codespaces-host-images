<!-- This file is auto-generated. Please do not edit this file directly. -->
<!-- Generated on: 2023-11-01T16:00:24.471Z -->

# Codespaces Host Image Configurations
The host image defines the operating system in which development containers run.
These images receive periodic upgrades for security, functionality, and performance. GitHub Codespaces offers early access to beta images to ensure compatibility with existing development container configurations.
We offer two host configuration channels to follow, stable and beta:
- **Stable:** Our default host. This is what you will receive if you do not specify that you would like to run on the beta channel.
- **Beta:** As we upgrade our machines or software packages, we offer a beta channel that allows you to validate your environments against new host configurations.         If you select to follow this channel, you will receive beta hosts if they are available. If there is no active beta configuration, you will receive the latest stable host configuration.
## Selecting your host configuration
You can select which host configuration they want to follow. When you select the Beta channel, you will receive the beta configuration if one is available, otherwise you will receive the Stable configuration.
By default you will be subscribed to the Stable channel.
# Host image definitions
## Stable
**Version**: 20231026001

**Host OS**: Ubuntu 22.04.3 LTS (Jammy Jellyfish)

### Installed Packages
| Package | Version | Description |
|---|---|---|
| moby-engine | 23.0.x | Docker container platform (engine package) |
| docker-compose | 1.29.x | Define and run multi-container applications with Docker. |
| nodejs | 18.17.x | Node.js event-based server-side javascript engine |
| python3 | 3.10.x | interactive high-level object-oriented language (default python3 version) |
| azcopy | 10.3.x | A command-line utility designed for copying data to/from Microsoft Azure Blob, File, and Table storage, using simple commands designed for optimal performance. |

## Beta
**Version**: 20231026001

**Host OS**: Ubuntu 22.04.3 LTS (Jammy Jellyfish)

### Installed Packages
| Package | Version | Description |
|---|---|---|
| moby-engine | 23.0.x | Docker container platform (engine package) |
| docker-compose | 2.22.x | Define and run multi-container applications with Docker. |
| nodejs | 18.17.x | Node.js event-based server-side javascript engine |
| python3 | 3.10.x | interactive high-level object-oriented language (default python3 version) |
| azcopy | 10.21.x | A command-line utility designed for copying data to/from Microsoft Azure Blob, File, and Table storage, using simple commands designed for optimal performance. |

