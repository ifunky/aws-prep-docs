---
title: "Tech Stack"
date: 2020-03-19T20:26:00Z
draft: false
weight: 3
---

**Overview**

The quick solution that I have created incorporates:

- Infrastratrucuture as Code
- DotNet Core Website
- Basic CI/CD pipeline build in TeamCity

**OS**

I chose Windows on this occasion purely because I wanted to create a basic pipeline in TeamCity and as this is an all in one box which requires an interface (for TeamCity) I selected Windows 2019.  If I didn't install TeamCity then I would have chosen Linux to run this on.

**Language**

I chose to use Dotnet core because I come from a .Net development background and this framework can run on Linux/Windows

**CI/CD**

I chose TeamCity for it simplicity, 3 free agents, ease of use and I have extensive knowledge using this.

Cake.Build as a build framework because it's based on .net and runscross platform

Additionally the solution provides:

- A `commit` pipeline that compiles and tests the code
- DevSecOps: Ability to run dependency checker (OWASP) to ensure we aren't using 3rd party libraries with vulnerabilites
- Very basic deployment after a sucessful build



**Automated Documentation**

This documentation is automated with the `AWS Amplify` framework :-)

AWS Well Archcitected Framework: Operational Excellence -> Annotated Documentation