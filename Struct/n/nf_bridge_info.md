# Struct: <code>nf_bridge_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    atomic_t use;
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    atomic_t use;
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    atomic_t use;
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    refcount_t use;
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    refcount_t use;
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    refcount_t use;
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    u8 sabotage_in_done;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    u8 sabotage_in_done;
    __u16 frag_max_size;
    int physinif;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
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
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
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
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nf_bridge_info {
    enum (anon) orig_proto;
    u8 pkt_otherhost;
    u8 in_prerouting;
    u8 bridged_dnat;
    __u16 frag_max_size;
    struct net_device * physindev;
    struct net_device * physoutdev;
    __be32 ipv4_daddr;
    struct in6_addr ipv6_daddr;
    char[8] neigh_header;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t use</code> ➡️ <code>refcount_t use</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>refcount_t use</code>
</li>
</ul>
</details>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 sabotage_in_done</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int physinif</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * physindev</code>
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
