# Struct: <code>pingv6_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
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
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
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
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pingv6_ops {
    int (*)(struct sock *, struct msghdr *, int, int *) ipv6_recv_error;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_common_ctl;
    void (*)(struct sock *, struct msghdr *, struct sk_buff *) ip6_datagram_recv_specific_ctl;
    int (*)(u8, u8, int *) icmpv6_err_convert;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) ipv6_icmp_error;
    int (*)(struct net *, const struct in6_addr *, const struct net_device *, int) ipv6_chk_addr;
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
