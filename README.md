<div align="center">
  <img src="./image/ktlogo.gif" alt="TCMinerProxy logo" width="96" />

  <h1>TCMinerProxy – Mining Pool Relay Proxy</h1>

  <p>
    <strong>Rust-based mining pool relay forwarding software with a brand-new architecture, representing the next-generation top-tier pool relay solution.</strong>
  </p>

  <p>
    Built for mining farms, pool operators, and infrastructure teams that need controlled hashrate allocation, reliable miner access, and clear operations tooling.
  </p>

  <p>
    <a href="https://tcminerproxy.com/">
      <img src="https://img.shields.io/badge/Website-tcminerproxy.com-7aa1ff?style=for-the-badge" alt="Website" />
    </a>
    <a href="https://github.com/MinerProxyPro/TCMinerProxy">
      <img src="https://img.shields.io/badge/Core-TCMinerProxy-5fd190?style=for-the-badge&logo=github&logoColor=white" alt="TCMinerProxy" />
    </a>
    <a href="https://github.com/MinerProxyPro/TMS">
      <img src="https://img.shields.io/badge/Client-TMS-7fc8ff?style=for-the-badge&logo=rust&logoColor=white" alt="TMS" />
    </a>
  </p>

  <p>
    <a href="https://t.me/tcminerproxy">
      <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" />
    </a>
    <a href="https://discord.gg/PCKrcNArBE">
      <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" />
    </a>
    <a href="https://x.com/tcminerproxy">
      <img src="https://img.shields.io/badge/X-tcminerproxy-000000?style=flat-square&logo=x&logoColor=white" alt="X" />
    </a>
    <a href="https://github.com/MinerProxyPro/TCMinerProxy/releases/latest">
      <img src="https://img.shields.io/github/v/release/MinerProxyPro/TCMinerProxy?style=flat-square&label=latest%20release" alt="Latest TCMinerProxy release" />
    </a>
  </p>
</div>

<p align="center">
  <img src="./image/rustminer-product-demo.webp" alt="TCMinerProxy product demo" width="100%" />
</p>

## Product Map

<table>
  <tr>
    <td width="33%" valign="top">
      <img src="./image/rust.png" alt="" width="36" />
      <h3>TCMinerProxy</h3>
      <p>
        The core proxy and operations console for miner access, third-party pool
        forwarding, port management, device statistics, logs, and allocation rules.
      </p>
      <p><a href="https://github.com/MinerProxyPro/TCMinerProxy">Open repository</a></p>
    </td>
    <td width="33%" valign="top">
      <img src="./image/rms.png" alt="" width="36" />
      <h3>TMS Secure Client</h3>
      <p>
        Optional local encrypted compression client for sites that want lower
        bandwidth usage and fewer public connections while keeping miners nearby.
      </p>
      <p>
        <a href="https://github.com/MinerProxyPro/TMS">TMS3</a>
        |
        <a href="https://github.com/MinerProxyPro/TMS/tree/main/OLD_2">TMS2</a>
      </p>
    </td>
    <td width="33%" valign="top">
      <img src="./image/safe.png" alt="" width="36" />
      <h3>PoolNode</h3>
      <p>
        Build a self-owned real mining pool node and distribute configured fees
        at the coin settlement layer instead of only at the forwarding layer.
      </p>
      <p>
        <a href="https://tcminerproxy.com/document/poolnode">Read PoolNode docs</a>
      </p>
    </td>
  </tr>
</table>

## What It Solves

| Area                  | Capability                                                                            |
| --------------------- | ------------------------------------------------------------------------------------- |
| Miner access          | Direct TCP/SSL access, or optional TMS encrypted compression for local sites          |
| Pool relay            | Forward connected miners to third-party pools with centralized port and route control |
| Hashrate allocation   | Route configured shares to specified pool wallets or worker names                     |
| PoolNode mode         | Run a real pool node and apply fees at settlement level                               |
| Operations            | Monitor hashrate, online/offline devices, latency, logs, versions, and system load    |
| Multi-site management | Manage local facilities, cloud nodes, clients, and regional access from one console   |

```text
Miner devices
    |
    | TCP / SSL or optional TMS encrypted compression
    v
TCMinerProxy
    |-- third-party pool relay and wallet allocation
    |-- PoolNode real-pool settlement workflow
    |-- dashboard, logs, device stats, and remote operations
```

## Featured Links

| Resource                                                                   | Description                                                        |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| [Official Website](https://tcminerproxy.com/)                              | Product overview, downloads, documentation, and multilingual pages |
| [TCMinerProxy](https://github.com/MinerProxyPro/TCMinerProxy)              | Core server, proxy engine, dashboard, and PoolNode system          |
| [TMS3](https://github.com/MinerProxyPro/TMS)                               | Current secure local client                                        |
| [RMS2](https://github.com/MinerProxyPro/TMS/tree/main/OLD_2)               | Legacy secure local client                                         |
| [TCMinerProxy Docs](https://tcminerproxy.com/document/tcminerproxy)        | Deployment, configuration, and operations guide                    |
| [TMS Docs](https://tcminerproxy.com/document/tms)                          | Secure client setup and network optimization workflow              |
| [TCMinerProxy CLI](https://tcminerproxy.com/document/tcminerproxy-cli)     | Command-line management documentation                              |
| [Downloads](https://tcminerproxy.com/download/tcminerproxy-core-server)    | Core server, secure client, and mobile app downloads               |

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Rust-core%20engine-d3452b?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Vue%203-frontend-42b883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue 3" />
  <img src="https://img.shields.io/badge/Vite-build%20tool-646cff?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Naive%20UI-interface-18a058?style=flat-square" alt="Naive UI" />
  <img src="https://img.shields.io/badge/ECharts-observability-aa7cff?style=flat-square&logo=apacheecharts&logoColor=white" alt="ECharts" />
  <img src="https://img.shields.io/badge/Linux-deployment-fcc624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

## Supported Workflows

| Workflow               | TCMinerProxy support                                                                      |
| ---------------------- | -------------------------------------------------------------------------------------------- |
| Third-party pool proxy | Route miners through a controlled forwarding layer                                           |
| Site-side optimization | Use TMS when bandwidth, public connections, or encrypted local access matter                 |
| Self-owned pool        | Use PoolNode to operate a real pool and settle configured fees at coin level                 |
| Custom management      | Extend operations with local APIs, remote clients, and tailored deployments                  |
| Community support      | Follow releases, deployment notes, and troubleshooting through GitHub, Telegram, Discord, X, and Reddit |

## Community

<p>
  <a href="https://github.com/MinerProxyPro">
    <img src="https://img.shields.io/badge/GitHub-MinerProxyPro-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://t.me/tcminerproxy">
    <img src="https://img.shields.io/badge/Telegram-tcminerproxy-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="https://discord.gg/PCKrcNArBE">
    <img src="https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <a href="https://x.com/tcminerproxy">
    <img src="https://img.shields.io/badge/X-tcminerproxy-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
</p>

> TCMinerProxy is infrastructure software for legitimate mining-farm and
> pool-operations scenarios. Users are responsible for following local laws,
> platform rules, and the requirements of the pools or services they connect to.
