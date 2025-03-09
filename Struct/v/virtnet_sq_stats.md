# Struct: <code>virtnet_sq_stats</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct virtnet_sq_stats {
    struct u64_stats_sync syncp;
    u64 packets;
    u64 bytes;
    u64 xdp_tx;
    u64 xdp_tx_drops;
    u64 kicks;
    u64 tx_timeouts;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct virtnet_sq_stats {
    struct u64_stats_sync syncp;
    u64_stats_t packets;
    u64_stats_t bytes;
    u64_stats_t xdp_tx;
    u64_stats_t xdp_tx_drops;
    u64_stats_t kicks;
    u64_stats_t tx_timeouts;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct virtnet_sq_stats {
    struct u64_stats_sync syncp;
    u64 packets;
    u64 bytes;
    u64 xdp_tx;
    u64 xdp_tx_drops;
    u64 kicks;
    u64 tx_timeouts;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u64 packets</code> ➡️ <code>u64_stats_t packets</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 bytes</code> ➡️ <code>u64_stats_t bytes</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 xdp_tx</code> ➡️ <code>u64_stats_t xdp_tx</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 xdp_tx_drops</code> ➡️ <code>u64_stats_t xdp_tx_drops</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 kicks</code> ➡️ <code>u64_stats_t kicks</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 tx_timeouts</code> ➡️ <code>u64_stats_t tx_timeouts</code>
</li>
</ul>
</details>
</li>
</ul>
