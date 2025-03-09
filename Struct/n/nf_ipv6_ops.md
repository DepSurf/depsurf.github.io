# Struct: <code>nf_ipv6_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    __sum16 (*)(struct sk_buff *, unsigned int, unsigned int, u_int8_t) checksum;
    __sum16 (*)(struct sk_buff *, unsigned int, unsigned int, unsigned int, u_int8_t) checksum_partial;
    int (*)(struct net *, struct dst_entry * *, struct flowi *, bool) route;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr;
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct net *, struct dst_entry * *, struct flowi *, bool) route;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
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
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
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
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nf_ipv6_ops {
    void (*)(struct sk_buff *) route_input;
    int (*)(struct net *, struct sock *, struct sk_buff *, int (*)(struct net *, struct sock *, struct sk_buff *)) fragment;
    int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__sum16 (*)(struct sk_buff *, unsigned int, unsigned int, u_int8_t) checksum</code>
</li>
<li>
<b>Field added. </b>
<code>__sum16 (*)(struct sk_buff *, unsigned int, unsigned int, unsigned int, u_int8_t) checksum_partial</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net *, struct dst_entry * *, struct flowi *, bool) route</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, const struct nf_queue_entry *) reroute</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__sum16 (*)(struct sk_buff *, unsigned int, unsigned int, u_int8_t) checksum</code>
</li>
<li>
<b>Field removed. </b>
<code>__sum16 (*)(struct sk_buff *, unsigned int, unsigned int, unsigned int, u_int8_t) checksum_partial</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) chk_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net *, struct dst_entry * *, struct flowi *, bool) route</code>
</li>
</ul>
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
