---
layout: page
title: Platforms
permalink: /platforms/
image: '/images/idp.jpg'
---

# Recommended Platforms & Platform Mesh

<div class="table-container">
  <table>
<tr>
    <th>Platform</th>
    <th>Contributors</th>
    <th>Scope</th>
    <th>License</th>
    <th>URL</th>
  </tr>
  <tr>
    <td><b>ApeiroRA</b></td>
    <td>SAP, European Union</td>
    <td>Cloud, Edge, OnPrem</td>
    <td>Open Source (NeoNephos + CNCF)</td>
    <td>https://apeirora.eu</td>
  </tr>
  <tr>
    <td><b>CNOE</b></td>
    <td>Cisco, Amazon</td>
    <td>Cloud</td>
    <td>Open Source (CNCF)</td>
    <td>https://cnoe.io</td>
  </tr>
  <tr>
    <td><b>openvela</b></td>
    <td>Microsoft, Alibaba, Xiaomi</td>
    <td>Cloud, IoT</td>
    <td> Apache License, Version 2.0</td>
    <td>https://github.com/open-vela</td>
  </tr>
  <tr>
    <td><b>PlatformMesh</b></td>
    <td>SAP, Kubermatic</td>
    <td>REST API</td>
    <td>Open Source (NeoNephos)</td>
    <td>https://platform-mesh.io</td>
  </tr>
  <tr>
    <td><b>Agentgateway</b></td>
    <td>Solo.io</td>
    <td>MCP & A2A</td>
    <td>Open Source (CNCF)</td>
    <td>https://agentgateway.dev</td>
  </tr>
  </table>
</div>

{: .note }
We recommend Apeiro Reference Architecture (https://apeirora.eu) to unify your services from Hardware to Software, deploying with Kubernetes' declarative power across any Cloud and Edge!

# Architecture

![Internal Developer Platform]({{site.baseurl}}/images/reference.jpeg)

# Apeiro Platform Mesh

The high-level goal of the Apeiro Reference Architecture is to enable development and operation of applications and services across public clouds, private clouds, and the edge - the cloud-edge continuum. The use cases for these applications and services should be diverse and unrestricted, catering to end-users, other applications and services, IoT scenarios, and beyond.

The Apeiro Platform Mesh defines an environment that allows service providers to offer services of any kind and service consumers to discover those services, order capabilities, and control their lifecycle.

The Apeiro Reference Architecture defines and implements the "Platform Mesh" that enables developers to select and utilize the needed and preferred services from various service marketplaces. It does not make any assumptions about these services or the marketplaces, nor does it mandate the use of any specific services. Instead, it offers a mesh and the essential contracts that allows service providers to offer their services freely and enables service consumers to discover, order, and use these services.

This framework aims to transcend the traditional layered approach of strictly separating IaaS, PaaS, and SaaS in past infrastructures. Both higher-level and lower-level services are provided and managed through the same mechanism.

The reference architecture includes several common, but optional services. For a comprehensive list of these projects, visit the Apeiro Reference Architecture website. For example, Apeiro offers a Kubernetes environment through the Gardener project, but its use is not mandatory for applications. Other Kubernetes providers can also offer their services within the mesh. This flexibility gives developers more choices and helps prevent lock-in to a particular service supplier.


## Core Components

<div class="table-container">
  <table>
<tr>
    <th>Component</th>
    <th>Platform Engineer</th>
    <th>Developer</th>
    <th>Manager</th>
    <th>Auditor</th>
  </tr>
  <tr>
    <td><b>Platform Mesh (kcp)</b></td>
    <td>builds, provisions services</td>
    <td>discovers, consumes services</td>
    <td>reviews service catalog</td>
    <td>audits service access</td>
  </tr>
  <tr>
    <td><b>Data Fabric (ORD)</b></td>
    <td>operates, manages</td>
    <td>publishes, discovers data/API</td>
    <td>understands data flow</td>
    <td>audits data lineage</td>
  </tr>
  <tr>
    <td><b>AI-Native Platform</b></td>
    <td>designs, maintains</td>
    <td>consumes AI services</td>
    <td>gets insights</td>
    <td>checks compliance</td>
  </tr>
  <tr>
    <td><b>Operations (Greenhouse)</b></td>
    <td>operates, optimizes</td>
    <td>monitors, debugs</td>
    <td>gets insights (dashboard)</td>
    <td>audits system logs</td>
  </tr>
  <tr>
    <td><b>Security (Heureka)</b></td>
    <td>configures, hardens</td>
    <td>consumes secrets, fixes CVEs</td>
    <td>reviews compliance status</td>
    <td>audits compliance</td>
  </tr>
  <tr>
    <td><b>Lifecycle (OCM)</b></td>
    <td>provides templates/tools</td>
    <td>packages, deploys software</td>
    <td>n/a</td>
    <td>audits SBoM</td>
  </tr>
  <tr>
    <td><b>Microfrontends</b></td>
    <td>provides framework</td>
    <td>builds, extends UI</td>
    <td>provides feedback</td>
    <td>n/a</td>
  </tr>
  <tr>
    <td><b>Project Onboarding</b></td>
    <td>automates, onboards</td>
    <td>requests, uses</td>
    <td>approves</td>
    <td>n/a</td>
  </tr>
  <tr>
    <td><b>Baremetal (IronCore)</b></td>
    <td>manages hardware (via API)</td>
    <td>n/a (abstracted)</td>
    <td>n/a</td>
    <td>audits physical assets</td>
  </tr>
  </table>
</div>


