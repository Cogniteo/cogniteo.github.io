---
layout: page
title: Internal Developer Platform
permalink: /idp/
image: '/images/idp.jpg'
---

# Platform Engineering

Platform Engineering is the practice of designing, building, and maintaining self-service platforms to improve developer experience and efficiency. It focuses on creating standardized infrastructure, automation, and workflows that enable developers to deploy and manage applications seamlessly. Platform engineers build Internal Developer Platforms (IDPs) that integrate CI/CD, security, observability, and cloud resources, reducing operational overhead and fostering innovation.

# Internal Developer Platform

An Internal Developer Platform (IDP) is a self-service set of tools and services designed to streamline software development and deployment within an organization. It provides developers with standardized workflows, automation, and infrastructure management, enabling them to build, test, and deploy applications efficiently without relying heavily on operations teams. IDPs typically integrate CI/CD pipelines, Kubernetes, cloud resources, observability, and security policies, improving productivity, consistency, and scalability across engineering teams.

## Roles 

{: .note }
Platform Engineer is both a Developer and a User of the Internal Developer Platform (according to the principle of: "eat your own dog food")

<div class="table-container">
  <table>
    <tr><th>Component</th><th>Platform Engineer</th><th>Developer</th><th>Manager</th><th>Auditor</th></tr>
    <tr><td><b>Internal Developer Platform</b></td><td>designs, builds, maintains</td><td>uses</td><td>uses</td><td>uses</td></tr>
    <tr><td><b>IDP DevEx</b></td><td>improves, extends</td><td>feedback</td><td>feedback</td><td>feedback</td></tr>
    <tr><td><b>New Project</b></td><td>onboards</td><td>follows</td><td>n/a</td><td>n/a</td></tr>
    <tr><td><b>CI/CD</b></td><td>template</td><td>customize</td><td>n/a</td><td>n/a</td></tr>
    <tr><td><b>Observability</b></td><td>tune, optimise</td><td>tune, optimise</td><td>insights</td><td>audit</td></tr>
    <tr><td><b>Security</b></td><td>harden</td><td>harden</td><td>n/a</td><td>audit</td></tr>
  </table>
</div>

## Architecture

![Internal Developer Platform]({{site.baseurl}}/images/reference.jpeg)
