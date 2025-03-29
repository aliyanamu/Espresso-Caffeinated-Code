# Espresso-Caffeinated-Code

1OK69GO (oneokrockgo) is an L3 rollup built on Arbitrum Orbit, designed for high-performance and scalable decentralized applications. The rollup is integrated with Espresso, leveraging its confirmation layer for enhanced security and faster transaction finality.

### Key Features

- **L3 Rollup**: 1OK69GO operates as an Arbitrum Orbit L3, offering low-cost and high-throughput transactions.
- **Espresso Integration**: The rollup is secured by Espresso's confirmation layer, improving decentralization and reducing reliance on sequencer trust.
- **Bridge Contracts**: Custom bridge contracts enable seamless asset transfers between Arbitrum Sepolia L2 and 1OK69GO L3.
- **Remote Server Infrastructure**:

  RPC URL: https://rpc.1ok69go.space (for interacting with the rollup)

  Caffeinated URL: https://caff.1ok69go.space (for connecting to Espresso’s confirmation layer)

### Adding To Metamask

| Property        | Value                     |
| --------------- | ------------------------- |
| Network Name    | 1OK69GO                   |
| RPC URL         | https://rpc.1ok69go.space |
| Chain ID        | 109695                    |
| Chain Name      | oneokrockgo               |
| Currency symbol | ETH                       |

### Adding To bridge.arbitrum.io

Steps:

1. Copy the following [1OK69GO.json](1OK69GO.json)
2. Click `From` / `To` to open Select Source Network. Make sure Testnet mode ON.
3. Click `Add Custom Orbit Chain`
4. Paste the JSON configuration and click `Add Chain`
5. Now, 1OK69GO can be searched on selected networks.
