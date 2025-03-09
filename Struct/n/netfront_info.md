# Struct: <code>netfront_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    bool broken;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    bool broken;
    bool bounce;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    bool broken;
    bool bounce;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    bool broken;
    bool bounce;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    bool netback_has_xdp_headroom;
    bool netfront_xdp_enabled;
    bool broken;
    bool bounce;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
    int freeze_state;
    struct completion wait_backend_disconnected;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool netback_has_xdp_headroom</code>
</li>
<li>
<b>Field added. </b>
<code>bool netfront_xdp_enabled</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool broken</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool bounce</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int freeze_state</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion wait_backend_disconnected</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct netfront_info {
    struct list_head list;
    struct net_device * netdev;
    struct xenbus_device * xbdev;
    struct netfront_queue * queues;
    struct netfront_stats * rx_stats;
    struct netfront_stats * tx_stats;
    atomic_t rx_gso_checksum_fixup;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
