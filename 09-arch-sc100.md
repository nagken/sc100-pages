# Architectures - SC-100

> Reference architectures you should be able to draw on a whiteboard for the exam.

## MCRA-aligned target state (high-level)

```mermaid
flowchart LR
    subgraph ID[Identity]
        Entra[Entra ID + Governance]
    end
    subgraph EP[Endpoints]
        Intune[Intune] --> DfE[Defender for Endpoint]
    end
    subgraph SOC
        Sentinel[Sentinel] --> XDR[Defender XDR]
    end
    subgraph Cloud
        DfC[Defender for Cloud] --> Arc[Azure Arc]
    end
    Entra --> Sentinel
    DfE --> XDR
    DfC --> Sentinel
```

## Ransomware-resilient design

```mermaid
flowchart TD
    Bk[Immutable backup vault] --> Recover
    PIM[PIM + tier-0 isolation] --> Limit
    EDR[MDE on every endpoint] --> Detect
    Net[Network segmentation] --> Limit
    Detect --> IR[IR playbook]
    IR --> Recover[Clean-room recovery]
```


---

[Master Index](00-MASTER-INDEX.md)
