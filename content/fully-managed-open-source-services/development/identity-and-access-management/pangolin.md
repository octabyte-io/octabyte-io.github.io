---
draft: false
title: Pangolin fully managed open source service | OctaByte.io
meta:
  cover: /images/development/identity-and-access-management/pangolin/screenshot-1.png
  description: Pangolin is a powerful, self-hosted reverse proxy and access gateway that uses encrypted WireGuard tunnels to securely expose private resources without opening ports—perfect for distributed networks and zero-trust environments.
  keywords: pangolin reverse proxy, self-hosted reverse proxy, WireGuard tunnel proxy, secure access gateway, firewall punching, remote access without port forwarding, identity access control reverse proxy, docker reverse proxy, encrypted tunnel proxy, zero-trust network access
  breadcrumb:
    - name: Home
      url: /
    - name: Software Catalog
      url: /fully-managed-open-source-services
    - name: Development
      url: /fully-managed-open-source-services/development
    - name: Identity and access management
      url: /fully-managed-open-source-services/development/identity-and-access-management
    - name: Pangolin
      url: /fully-managed-open-source-services/development/identity-and-access-management/pangolin
content:
  id: pangolin
  name: Pangolin
  title: Secure Self-Hosted Reverse Proxy with Identity and Access Control
  logo: /images/development/identity-and-access-management/pangolin/logo.png
  website: https://fossorial.io/
  iframe_website: /website/development/identity-and-access-management/pangolin
  screenshots:
    - /images/development/identity-and-access-management/pangolin/screenshot-1.png
    - /images/development/identity-and-access-management/pangolin/screenshot-2.png
---

## Overview

Pangolin is a security-focused, self-hosted reverse proxy system that connects isolated and firewalled networks via encrypted WireGuard tunnels. It simplifies secure access to private services by eliminating the need for port forwarding, while offering centralized user management, detailed access control, and seamless deployment on any infrastructure. Designed with both simplicity and scalability in mind, Pangolin empowers teams to securely manage distributed services with modern identity-first principles.

## Features

- ### WireGuard Tunnel-Based Reverse Proxy

  Expose internal services securely without opening ports using encrypted WireGuard tunnels. Supports raw TCP/UDP and HTTP/HTTPS protocols, with built-in load balancing.

- ### Custom User-Space WireGuard Client – Newt

  Enjoy simplified and optimized site-to-site connectivity with Newt, Pangolin’s custom WireGuard client, or connect using any standard WireGuard client.

- ### Automated SSL with Let’s Encrypt

  Ensure all exposed services are protected with HTTPS using automated SSL certificate provisioning via Let’s Encrypt.

- ### Centralized Identity & Access Management

  Leverage platform SSO for seamless authentication, two-factor support (TOTP), and role-based access control with scoped API keys and fine-grained permissions.

- ### Modern Dashboard UI

  Easily manage users, roles, and remote sites through a responsive dashboard with light/dark themes and mobile compatibility. Monitor site connectivity and activity in real-time.

- ### Easy, Scalable Deployment

  Deploy Pangolin effortlessly using Docker Compose. Install it on any cloud provider or on-premises system. Extend functionality via REST API and automate tasks with comprehensive documentation.
