---
title: "JAM Stack"
date: 2020-03-24T09:14:50Z
draft: false
---

***JAMstack** stands for JavaScript, APIs, and Markup. The term was coined by Mathias Biilmann to describe a modern web development architecture based on client-side JavaScript, reusable APIs, and prebuilt Markup. The static nature of a **JAMstack** app makes scaling easy, and causes little to no dev-ops overhead.*

https://jamstack.org/

**Overview**

The concept behind this site is to create a complete serverless documentation website.

**Tools**

- Hugo - A static site generator based on markdown
- Git - source of truth for gitops enabled pipelines
- AWS Amplify - provides CI/CD and serverless content hosting



**Why**

- Completely take advantage of the AWS shared responsibility model 
- No need to worry about instance size or scaling
- Superfast performance due to running behind a CDN
- Very cheap to buyild and run

**How**

- This site is controlled bit git: https://github.com/ifunky/aws-prep-docs
- AWS Amplify is used to build and deploy the site.  simple :-)

