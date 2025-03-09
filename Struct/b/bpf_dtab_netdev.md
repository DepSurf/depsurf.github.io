# Struct: <code>bpf_dtab_netdev</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct bpf_dtab * dtab;
    unsigned int bit;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct bpf_dtab * dtab;
    unsigned int bit;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct bpf_dtab * dtab;
    unsigned int bit;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct bpf_dtab * dtab;
    unsigned int bit;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_prog * xdp_prog;
    struct callback_head rcu;
    unsigned int idx;
    struct bpf_devmap_val val;
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
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
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
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct hlist_node index_hlist;
    struct bpf_dtab * dtab;
    struct xdp_bulk_queue * bulkq;
    struct callback_head rcu;
    unsigned int idx;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_dtab_netdev {
    struct net_device * dev;
    struct bpf_dtab * dtab;
    unsigned int bit;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xdp_bulk_queue * bulkq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node index_hlist</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int idx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int bit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bpf_prog * xdp_prog</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_devmap_val val</code>
</li>
<li>
<b>Field removed. </b>
<code>struct xdp_bulk_queue * bulkq</code>
</li>
</ul>
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct bpf_dtab * dtab</code>
</li>
</ul>
</details>
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
