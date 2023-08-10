# Keycloak-FIDO

## Table of Contents
- [Purpose or Introduction](#purpose-or-introduction)
- [Getting Started](#getting-started)
   * [Configuration (Windows)](#configuration-windows)
   * [Usage](#usage)

## Purpose

The Keycloak-FIDO project serves as a demonstration of how Keycloak can be configured to work with FIDO2 authentication.\
As technology continuously advances, so does the need for more secure authentication methods.\
This project seeks to bridge the capabilities of Keycloak, a widely recognized identity and access management solution, with the robustness of FIDO2, a modern authentication standard.\
Whether you're a developer looking to implement more secure authentication mechanisms or an enthusiast trying to understand the intersection of these technologies, this Proof of Concept (PoC) aims to guide and inform.

## Getting Started

### Configuration (Windows)

To configure Keycloak for FIDO2, follow the steps below. These steps ensure compatibility with the security precautions of Keycloak, Apple Keychain, and browser vendors. Additionally, after following these steps, you can access the Keycloak server from your mobile device.

1. **Run the docker-compose.yml**

    ```
    docker-compose up
    ```

2. **Install Apple Bonjour** for mDNS configuration:

   [Download from Apple Developer](https://developer.apple.com/bonjour/)

3. **Find out the hostname of your computer**:

    - Press `WIN + R`.
    - Type `cmd` and press Enter.

    ```
    hostname
    ```

   This might return something like `DESKTOP-ABCXYZ`.

4. **Access Keycloak in Your Browser**:

   Open the following URL, replacing `<hostname>` with the name returned from the previous step: `https://<hostname>.local/`\
   For example: https://desktop-abcxyz.local/

### Usage

tbd
