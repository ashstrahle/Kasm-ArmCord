# Kasm-ArmCord
**Discord ARM64 Client** for Kasm (Ideal Discord client for Raspberry Pi)

This distro creates a custom Kasm ArmCord ARM64 Discord client image.

## Installation

- Run the following to create the required Docker image:

      docker build -t armcord -f Dockerfile .

- Create the Kasm image as per below:

![](/docs/ArmCord.png)

- Be sure to configure **Persistent Profile Path** so that user details are saved.

Enjoy!