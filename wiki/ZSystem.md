_ZSystem_ is an arbitrary term used to describe Valheim's netcode as a whole. Valheim, for all intents and purposes, uses a [Peer-to-Peer](https://en.wikipedia.org/wiki/Peer-to-peer) architecture for connecting players to a single long-lived session. Simply put, each client (i.e. player) connected to a server regularly shares the state of their game with all other clients, which is used to synchronize game states for everyone. It is made up of many interrelated components, each one playing a part in making multiplayer possible. Below is a mapping of components and their relationships to one another.

<details>
  <summary>ZNet</summary>

* ZDOMan
* ZRoutedRpc
</details>
<details>
  <summary>ZNat</summary>
</details>
<details>
  <summary>ZNetPeer</summary>
</details>
<details>
  <summary>ZNetScene</summary>
</details>
<details>
  <summary>ZNetView</summary>
</details>
<details>
  <summary>ZNetStats</summary>
</details>
<details>
  <summary>ZNtp</summary>
</details>
<details>
  <summary>ZDOPeer</summary>
</details>
<details>
  <summary>ZDOMan</summary>
</details>
<details>
  <summary>ZDOPool</summary>
</details>
<details>
  <summary>ZRoutedRpc</summary>
</details>
<details>
  <summary>ZRpc</summary>
</details>
<details>
  <summary>ZPackage</summary>
</details>
<details>
  <summary>ZSyncTransform</summary>
</details>
<details>
  <summary>ZSyncAnimation</summary>
</details>