---
title: "What I Self-Hosted on 7-Year-Old Hardware"
date: 2026-09-12
summary: "Learn more about me and why I am starting this blog."
description: "This is a demo of adding content to the homepage."
tags:
  [
    "selfhosting",
    "pihole",
    "traefik",
    "Home Assistant",
    "Jellyfin",
    "Joplin",
    "n8n",
    "grist",
    "dawarich",
    "Airtrail",
    "vaultwarden",
  ]
featureimage: "https://images.pexels.com/photos/12266914/pexels-photo-12266914.jpeg"
showHero: true
heroStyle: "thumbAndBackground"
showSummary: true
---

I've been self-hosting a few services on my 7-year-old laptop for almost a year now. In this article, let's go through these services and see how they contribute to my everyday life.

## 1. [Pi-hole](https://pi-hole.net/)

This is my DNS of choice. Earlier, I was using AdGuard for my DNS, but then I switched to Pi-hole, and it blocks almost 5 million domains for my home. I love the UI, and I don't have to make any changes to it. It just runs in the background and provides protection for my family.
![Pi-hole dashboard](images/pihole.png)

## 2. [Traefik](https://traefik.io/traefik)

Traefik is my choice of reverse proxy. I have been using this with Docker for years now. It handles certificate generation while assigning domains to all my services.
![Traefik](images/traefik.png)

## 3. [n8n](https://n8n.io)

n8n is an automation tool, and I have been using it to automate tracking my UPI transactions to a spreadsheet that I self-host and control. Every time I make a UPI transaction, it is automatically added to the spreadsheet, and then I can apply filters to see all of my financial transactions in one place. I'm planning to add credit card transactions to it as well.
![n8n](images/n8n.png)

## 4. [Grist](https://www.getgrist.com/)

Grist is where my financial transactions stay private. It contains all the UPI transactions that come from n8n, making personal finance easy for me. I don't have to manually add every transaction to it.
![grist](images/grist.png)

## 5. [Dawarich](https://dawarich.app/)

It is an open-source, self-hosted version of Google Timeline. It tracks all my trips. You can use the official application to track your location, and it syncs as soon as you connect to your home network. It also supports Immich and PhotoPrism to show all the photos that you took during the trip. In addition, there is [Airtrail](https://airtrail.johan.ohly.dk/), which handles air travel since Dawarich doesn't support it natively. You can integrate it with Airtrail to keep all your travel history in one place.

## 6. [Joplin](https://joplinapp.org/)

Recently, I migrated all our notes from applications like Notion, Google Keep, and OneNote to take control of our digital life. I came across Joplin and migrated all our notes to it. It has a backend sync service that you can self-host, and it will sync all your notes between multiple devices.
![joplin](images/joplin.png)

## 7. [Vaultwarden](https://www.vaultwarden.net/)

For my password manager, I'm using Vaultwarden. I hooked it into the Bitwarden client, and it works flawlessly. I love how nicely it integrates and that it requires very few resources.

![vaultwarden](images/vaultwarden.png)

Happy Self-Hosting!
