# Systemd Centos Container Images For Ansible and Podman

Systemd Centos Container Images for testing roles with Molecule and Podman.
Supported Centos versions:

* `7`

## Available Images

Images are built weekly via GitHub Actions and can be downloaded from the
GitHub Package Registry.

These tags are available. They are updated on changes to the `main` branch
and are automatically rebuilt once a week.

* `ghcr.io/hifis-net/centos-systemd:7`

## How to Use

* [Install Podman](https://podman.io/getting-started/installation)
* Run the container via Podman:

  ```bash
  podman run -it --systemd=true --privileged ghcr.io/hifis-net/centos-systemd:7
  ```

## Authors

This project is maintained by [HIFIS](https://www.hifis.net).
It is built upon https://github.com/geerlingguy/docker-centos7-ansible.
