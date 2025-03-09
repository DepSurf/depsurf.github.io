# Struct: <code>netlink_broadcast_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
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
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
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
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netlink_broadcast_data {
    struct sock * exclude_sk;
    struct net * net;
    u32 portid;
    u32 group;
    int failure;
    int delivery_failure;
    int congested;
    int delivered;
    gfp_t allocation;
    struct sk_buff * skb;
    struct sk_buff * skb2;
    int (*)(struct sock *, struct sk_buff *, void *) tx_filter;
    void * tx_data;
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
<b>Field removed. </b>
<code>int (*)(struct sock *, struct sk_buff *, void *) tx_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>void * tx_data</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_buff *, void *) tx_filter</code>
</li>
<li>
<b>Field added. </b>
<code>void * tx_data</code>
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
