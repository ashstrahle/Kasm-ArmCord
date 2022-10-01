# Kasm-ArmCord
**Discord ARM64 Client** for Kasm (Ideal for Raspberry Pi)

Containerised Discord client, streamed to your browser, running on a Raspberry Pi 😳

![](/docs/armcord-screenshot1.png)

![](/docs/armcord-screenshot2.png)


This distro creates a custom Kasm ArmCord ARM64 Discord client image.

## Installation

- Run the following to create the required Docker image:

      docker build -t armcord -f Dockerfile .

- Create the Kasm image as per below:

![](/docs/armcord-setup.png)

- Be sure to configure **Persistent Profile Path** so that user details are saved.

Enjoy!