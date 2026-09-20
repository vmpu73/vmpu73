## Infrastructure, measured rather than assumed

I run a nested VMware lab and write down what actually happens in it — including
the parts that contradict the documentation. Everything published here was
verified against real equipment before it was written.

### 📦 Toolkits

| | |
|---|---|
| **[nsx-collect-toolkit](https://github.com/vmpu73/nsx-collect-toolkit)** | On-box packet capture and state collection for NSX Edge and ESXi. Nothing is installed on the target. |
| **[avi-migration-kit](https://github.com/vmpu73/avi-migration-kit)** | NSX-T native LB → Avi (NSX ALB): what the ACT conversion tool does and does not do, and how to run both load balancers in parallel behind GSLB while traffic shifts gradually. |
| **[esxi-numa-diag](https://github.com/vmpu73/esxi-numa-diag)** | Read-only NUMA scheduler diagnostics. Locality migration rate against memory locality, so you can tell whether `Numa.LocalityWeightActionAffinity` is worth touching. |

Browse by topic: [`toolkit`](https://github.com/vmpu73?tab=repositories&q=topic%3Atoolkit) ·
[`nsx`](https://github.com/vmpu73?tab=repositories&q=topic%3Ansx) ·
[`esxi`](https://github.com/vmpu73?tab=repositories&q=topic%3Aesxi) ·
[`avi`](https://github.com/vmpu73?tab=repositories&q=topic%3Aavi)

### What I work on

VMware Cloud Foundation, NSX-T/NSX ALB, vSphere, and the monitoring stack around
them (Aria Operations / Operations for Logs). Lately: rebuilding a VCF 9.1.1
nested lab on a single host, and running Kubernetes next to it to see where the
two models disagree.

Lab records and internal knowledge bases are kept private.
