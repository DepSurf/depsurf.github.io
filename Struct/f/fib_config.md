# Struct: <code>fib_config</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    dscp_t fc_dscp;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    dscp_t fc_dscp;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    dscp_t fc_dscp;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    dscp_t fc_dscp;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
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
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
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
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fib_config {
    u8 fc_dst_len;
    u8 fc_tos;
    u8 fc_protocol;
    u8 fc_scope;
    u8 fc_type;
    u8 fc_gw_family;
    u32 fc_table;
    __be32 fc_dst;
    __be32 fc_gw4;
    struct in6_addr fc_gw6;
    int fc_oif;
    u32 fc_flags;
    u32 fc_priority;
    __be32 fc_prefsrc;
    u32 fc_nh_id;
    struct nlattr * fc_mx;
    struct rtnexthop * fc_mp;
    int fc_mx_len;
    int fc_mp_len;
    u32 fc_flow;
    u32 fc_nlflags;
    struct nl_info fc_nlinfo;
    struct nlattr * fc_encap;
    u16 fc_encap_type;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 fc_gw_family</code>
</li>
<li>
<b>Field added. </b>
<code>__be32 fc_gw4</code>
</li>
<li>
<b>Field added. </b>
<code>struct in6_addr fc_gw6</code>
</li>
<li>
<b>Field added. </b>
<code>u32 fc_nh_id</code>
</li>
<li>
<b>Field removed. </b>
<code>__be32 fc_gw</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>dscp_t fc_dscp</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 fc_tos</code>
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
