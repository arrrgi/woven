# Woven

Opinionated Ansible provisioner for a Digital Ocean VPS Wireguard gateway

## Background

This project is inspired by existing projects like Algo and Streisand to automate the deployment and provisioning of a cloud based virtual server pre-configured as a VPN endpoint. I decided to take what I thought were the best bits of both projects and combine them into a single Ansible playbook, using my preferred cloud infrastructure provider Digital Ocean and preferred VPN client, Wireguard.

Trivia: The name of the project is a play on the words *Ocean, Wireguard and VPN*

## Playbook Structure

Order of playbook execution:

1. Bootstrap - Tasks to provision a DO VM
2. System - Tasks to configure packages, services, etc
3. Secure - Tasks to secure the VM
4. Wireguard - Tasks to install Wireguard and create VPN profiles
5. Web - Tasks to publish profiles and instructions

## Requirements

Ansible version:
Wireguard client:
Digital Ocean API Token:
Digital Ocean Region ID:

## Installation

git clone repository or download Zip package

## Deployment

Run ansible-playbook

## Contributing