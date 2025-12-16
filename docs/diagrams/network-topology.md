# Network Topology

Diagram the network paths and addressing.

```mermaid
flowchart LR
  LAN[(Ops LAN)] --> Switch
  Switch --> GS[Groundstation]
  GS --> PadLink[Pad Link/Radio]
  PadLink --> Vehicle
```

Include VLANs, IP ranges, and link characteristics.
