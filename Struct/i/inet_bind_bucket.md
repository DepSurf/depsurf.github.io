# Struct: <code>inet_bind_bucket</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    int num_owners;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    int num_owners;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    int num_owners;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head bhash2;
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
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
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
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_bind_bucket {
    possible_net_t ib_net;
    int l3mdev;
    short unsigned int port;
    signed char fastreuse;
    signed char fastreuseport;
    kuid_t fastuid;
    struct in6_addr fast_v6_rcv_saddr;
    __be32 fast_rcv_saddr;
    short unsigned int fast_sk_family;
    bool fast_ipv6_only;
    struct hlist_node node;
    struct hlist_head owners;
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
<b>Field added. </b>
<code>struct in6_addr fast_v6_rcv_saddr</code>
</li>
<li>
<b>Field added. </b>
<code>__be32 fast_rcv_saddr</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int fast_sk_family</code>
</li>
<li>
<b>Field added. </b>
<code>bool fast_ipv6_only</code>
</li>
<li>
<b>Field removed. </b>
<code>int num_owners</code>
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
<b>Field added. </b>
<code>int l3mdev</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_head bhash2</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_head owners</code>
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
