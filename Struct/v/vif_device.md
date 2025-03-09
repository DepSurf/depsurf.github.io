# Struct: <code>vif_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    __be32 local;
    __be32 remote;
    int link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    __be32 local;
    __be32 remote;
    int link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    __be32 local;
    __be32 remote;
    int link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    __be32 local;
    __be32 remote;
    int link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    struct netdev_phys_item_id dev_parent_id;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    __be32 local;
    __be32 remote;
    int link;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    netdevice_tracker dev_tracker;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
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
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vif_device {
    struct net_device * dev;
    long unsigned int bytes_in;
    long unsigned int bytes_out;
    long unsigned int pkt_in;
    long unsigned int pkt_out;
    long unsigned int rate_limit;
    unsigned char threshold;
    short unsigned int flags;
    int link;
    struct netdev_phys_item_id dev_parent_id;
    __be32 local;
    __be32 remote;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct netdev_phys_item_id dev_parent_id</code>
</li>
</ul>
</details>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
