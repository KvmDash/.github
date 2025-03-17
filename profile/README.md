# Project Description: KVMDash

<table style="border-collapse: collapse; width: 100%;">
    <tr>
        <td style="width: 150px; padding: 10px; vertical-align: middle;">
            <img src="frontend/src/assets/kvmdash.svg" alt="KvmDash Logo" style="max-width: 100%;">
        </td>
        <td style="padding: 10px; vertical-align: middle;">
            KVMDash is a web application that enables the management of Virtual Machines (VMs) on Linux systems.
            With a user-friendly interface, KVMDash facilitates the administration and monitoring of virtualization environments.
        </td>
    </tr>
</table>

## 📑 Table of Contents
- [Features](#features)
- [Demo Videos](#demo-videos)
- [System Requirements](#system-requirements)
- [Installation](#installation)
  - [1. Install System Requirements](#1-install-system-requirements)
  - [2. Install KVMDash](#2-install-kvmdash)
  - [3. Set Up Backend](#3-set-up-backend)
  - [4. Set Up Frontend](#4-set-up-frontend)
  - [5. Set Up Web Server](#5-set-up-web-server)
  - [6. Direct Testing Without Apache (Development Environment)](#6-direct-testing-without-apache-development-environment)
- [Documentation](#documentation)

## Features

### VM Management
* Create, delete, and configure VMs and containers through the web interface.
* Use templates for quick and standardized creation of VMs.

### System Monitoring
* Real-time monitoring of resources such as CPU, memory, disk usage, and other important system metrics.
* Clear visualization of system performance for optimal control and error analysis.

## Demo Videos

https://github.com/user-attachments/assets/ec76e8fa-f9b1-487d-87a8-6d370dbfb73c

## System Requirements

* Node.js 18.x or newer
* npm 9.x or newer
* Composer 2.x
* KVM and libvirt
* Apache Web Server with PHP 8.2


Additional documentation:
- [Installation](https://github.com/KvmDash/kvmdash/blob/main/README.md)
- [KVM Installation and Configuration](docs/en/kvm-Debian.en.md)
- [Libvirt Setup and Management](docs/en/libvirt-Debian.en.md)
- [Apache Web Server Configuration](docs/en/apache-Debian.en.md)

## TurnKey Linux Compatibility

KVMDash works seamlessly with [TurnKey Linux](http://mirror.turnkeylinux.org/turnkeylinux/images/iso/) images. With TurnKey Linux, you get access to over 100 pre-built, ready-to-use server appliances based on Debian.

### Integration Benefits:
- **Rapid Deployment**: Immediately ready-to-use specialized servers without complex configuration
- **Wide Range**: From web server stacks (LAMP, LEMP) to CMS (WordPress, Drupal) and collaboration tools
- **Security**: Regularly updated, hardened images with automatic security updates

### Using TurnKey Images in KVMDash:
1. Download the desired TurnKey image from the official website
2. Import the image into KVMDash as a VM template
3. Create new VMs based on these templates with just a few clicks

TurnKey images provide an ideal complement to KVMDash for quickly deploying productive server environments without having to perform complex manual configurations.





