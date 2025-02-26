---
slug: /endpoints-overview
title: Endpoints 
---

# Ways to access Lava RPC

## Incentivized Public Endpoints

Lava works with various blockchains to establish **Incentivized Public RPC (ipRPC) endpoints**. ipRPC endpoints are given unified URLs serviced by diverse providers of each chain's ecosystem. Providers are paid by those respective ecosystems to offer their services and developers benefit from the availability of highly-serviced endpoints unified through a single URL.

<center> 

```mermaid

 flowchart LR
    A[dApp in the US] --> B(ipRPC URL)
    B --> C{Lava Network}
    C -->|US, 100ms| D[Provider1]
    C -->|US, 200ms| E[Provider2]
    C -->|US, 130ms| F[Provider3]
    C -->|US, 400ms| G[Provider4]

```

</center>

<br/>


## Lava Gateway

The **Lava Gateway** is a simplified web interface that gives developers instant access to blockchain data. The Gateway uses Lava Server Kit to provide a hosted point of access for developers looking for RPC through the Lava Network. This allows users to manage and configure Web3 APIs through an intuitive controls directly from the browser.

**Features**

1. Easy and intuitive interface for API access
2. Example calls for each supported chain


## Public Community Endpoints

Community endpoints are RPC endpoints provided by various community members and organizations. These endpoints offer free access to blockchain data, though availability and performance may vary as they are maintained by different providers.

