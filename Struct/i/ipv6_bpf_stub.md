# Struct: <code>ipv6_bpf_stub</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) ipv6_setsockopt;
    int (*)(struct sock *, int, int, sockptr_t, sockptr_t) ipv6_getsockopt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) ipv6_setsockopt;
    int (*)(struct sock *, int, int, sockptr_t, sockptr_t) ipv6_getsockopt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) ipv6_setsockopt;
    int (*)(struct sock *, int, int, sockptr_t, sockptr_t) ipv6_getsockopt;
    int (*)(struct net *, const struct net_device *, const struct in6_addr *, unsigned int, struct in6_addr *) ipv6_dev_get_saddr;
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
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
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
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
    struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct ipv6_bpf_stub {
    int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct sock * (*)(struct net *, const struct in6_addr *, __be16, const struct in6_addr *, __be16, int, int, struct udp_table *, struct sk_buff *) udp6_lib_lookup</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, struct sockaddr *, int, bool, bool) inet6_bind</code> ➡️ <code>int (*)(struct sock *, struct sockaddr *, int, u32) inet6_bind</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, int, int, sockptr_t, unsigned int) ipv6_setsockopt</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, int, int, sockptr_t, sockptr_t) ipv6_getsockopt</code>
</li>
</ul>
</details>
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
<code>int (*)(struct net *, const struct net_device *, const struct in6_addr *, unsigned int, struct in6_addr *) ipv6_dev_get_saddr</code>
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
