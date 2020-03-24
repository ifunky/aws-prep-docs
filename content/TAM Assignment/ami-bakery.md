---
title: "AMI Bakery"
date: 2020-03-19T20:22:47Z
draft: false
weight: 2
---

**How I Built My AMI**

The next step in the process was to build a base AMI image to work from.

**Technology Choice**

Hashicorp Packer

**Why?**

I find Packer is a great tool to easily automate and script AWS AMI building

**AWS Well Architected Framework**

This touches on:

- Security pillar:  Defence in depth, OS hardened image, OS level firewall, minimal software installed (lower attack area)
- Operational Excellence: Infrastructture as code

**Tools Used**

AMI Bakery: https://github.com/ifunky/bakery

An opensource framework I created to easily create Linux and Windows images

PolyDev:  https://github.com/ifunky/polydevAll 
An all in one DevOps tooling container 

