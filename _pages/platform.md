---
layout: page
title: Platform
permalink: /platform/
image: '/images/idp.jpg'
---

{: .note }
We recommend Apeiro Reference Architecture (https://apeirora.eu) to unify your services from Hardware to Software, deploying with Kubernetes' declarative power across any Cloud and Edge!

## Recommended Platforms

<div class="table-container">
  <table>
<tr>
    <th>Platform</th>
    <th>Contributors</th>
    <th>Scope</th>
    <th>Budget</th>
    <th>License</th>
    <th>URL</th>
  </tr>
  <tr>
    <td><b>ApeiroRA</b></td>
    <td>SAP, European Union</td>
    <td>Cloud, Edge, OnPrem</td>
    <td>3,5~ bln Euro</td>
    <td>Open Source (NeoNephos + CNCF)</td>
    <td>https://apeirora.eu</td>
  </tr>
  <tr>
    <td><b>CNOE</b></td>
    <td>Cisco, Amazon</td>
    <td>Cloud</td>
    <td>Best Effort</td>
    <td>Open Source (CNCF)</td>
    <td>https://cnoe.io</td>
  </tr>
  <tr>
    <td><b>openvela</b></td>
    <td>Microsoft, Alibaba, Xiaomi</td>
    <td>Cloud, IoT</td>
    <td>Best Effort</td>
    <td> Apache License, Version 2.0</td>
    <td>https://github.com/open-vela</td>
  </tr>
  </table>
</div>


## Architecture

![Internal Developer Platform]({{site.baseurl}}/images/reference.jpeg)

## Platform Components

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


