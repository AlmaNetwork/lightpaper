# 3.7 Region

ALMA's fundamental entities, such as IDs, schemata, instances, and nodes, are managed within a unit called "**region**". Each region has its own rule and governance. A region may be a centralized system, or a decentralized one. A region may allow anyone to register a new ID, or allow only specific people. In this respect, a region is comparable to a private network on the Internet.

A region is organized by multiple participant nodes. By using [MPC](../../5.-terminology/5.2-multi-party-computation-mpc.md), keys and data are distributed among the nodes in the region in a privacy-preserving manner. A node can select regions to join and contribute, and can belong to multiple regions.

<figure><img src="../../../.gitbook/assets/region network.jpg" alt=""><figcaption><p>Figure 4: Regions can be connected with each other.</p></figcaption></figure>

Regions can be connected with each other. Instances can be transferred not only within the region itself but also to the connected regions. Interoperability between regions will be explained later in [Section 3.8](../3.8-interoperability-between-regions/).
