# Struct: <code>ndisc_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
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
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
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
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct ndisc_ops {
    int (*)(u8) is_useropt;
    int (*)(const struct net_device *, struct nd_opt_hdr *, struct ndisc_options *) parse_options;
    void (*)(const struct net_device *, struct neighbour *, u32, u8, const struct ndisc_options *) update;
    int (*)(const struct net_device *, u8, struct neighbour *, u8 *, u8 * *) opt_addr_space;
    void (*)(const struct net_device *, struct sk_buff *, u8, const u8 *) fill_addr_option;
    void (*)(struct net *, struct net_device *, const struct prefix_info *, struct inet6_dev *, struct in6_addr *, int, u32, bool, bool, __u32, u32, bool) prefix_rcv_add_addr;
}
```
</details>
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
