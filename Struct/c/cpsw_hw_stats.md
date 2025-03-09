# Struct: <code>cpsw_hw_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpsw_hw_stats {
    u32 rxgoodframes;
    u32 rxbroadcastframes;
    u32 rxmulticastframes;
    u32 rxpauseframes;
    u32 rxcrcerrors;
    u32 rxaligncodeerrors;
    u32 rxoversizedframes;
    u32 rxjabberframes;
    u32 rxundersizedframes;
    u32 rxfragments;
    u32[2] __pad_0;
    u32 rxoctets;
    u32 txgoodframes;
    u32 txbroadcastframes;
    u32 txmulticastframes;
    u32 txpauseframes;
    u32 txdeferredframes;
    u32 txcollisionframes;
    u32 txsinglecollframes;
    u32 txmultcollframes;
    u32 txexcessivecollisions;
    u32 txlatecollisions;
    u32 txunderrun;
    u32 txcarriersenseerrors;
    u32 txoctets;
    u32 octetframes64;
    u32 octetframes65t127;
    u32 octetframes128t255;
    u32 octetframes256t511;
    u32 octetframes512t1023;
    u32 octetframes1024tup;
    u32 netoctets;
    u32 rxsofoverruns;
    u32 rxmofoverruns;
    u32 rxdmaoverruns;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct cpsw_hw_stats {
    u32 rxgoodframes;
    u32 rxbroadcastframes;
    u32 rxmulticastframes;
    u32 rxpauseframes;
    u32 rxcrcerrors;
    u32 rxaligncodeerrors;
    u32 rxoversizedframes;
    u32 rxjabberframes;
    u32 rxundersizedframes;
    u32 rxfragments;
    u32[2] __pad_0;
    u32 rxoctets;
    u32 txgoodframes;
    u32 txbroadcastframes;
    u32 txmulticastframes;
    u32 txpauseframes;
    u32 txdeferredframes;
    u32 txcollisionframes;
    u32 txsinglecollframes;
    u32 txmultcollframes;
    u32 txexcessivecollisions;
    u32 txlatecollisions;
    u32 txunderrun;
    u32 txcarriersenseerrors;
    u32 txoctets;
    u32 octetframes64;
    u32 octetframes65t127;
    u32 octetframes128t255;
    u32 octetframes256t511;
    u32 octetframes512t1023;
    u32 octetframes1024tup;
    u32 netoctets;
    u32 rxsofoverruns;
    u32 rxmofoverruns;
    u32 rxdmaoverruns;
}
```
</details>
</li>
</ul>
