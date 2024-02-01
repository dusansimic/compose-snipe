# Snipe-IT service

Docker Compose sets up the following containers:

* [Snipe-IT](#snipe-it) service container
* [MySQL](#myql) container

> [!IMPORTANT]
> This configuration expects that a reverse proxy handles SSL/TLS and rounting
> to the Snipe-IT endpoint.

## Prerequisites

These roles require `community.docker>=3.6.0` collection to function correctly.
A requirements file is available in `ansible/requirements.yaml`. To make sure,
the correct collection is installed, run `ansible-galaxy collection install -r ansible/requirements.yaml`.

## Snipe-IT

Currently no options are available.

## MySQL

Currently no options are available.
