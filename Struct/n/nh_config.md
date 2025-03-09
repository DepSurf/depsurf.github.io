# Struct: <code>nh_config</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    u16 nh_grp_res_num_buckets;
    long unsigned int nh_grp_res_idle_timer;
    long unsigned int nh_grp_res_unbalanced_timer;
    bool nh_grp_res_has_num_buckets;
    bool nh_grp_res_has_idle_timer;
    bool nh_grp_res_has_unbalanced_timer;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    u16 nh_grp_res_num_buckets;
    long unsigned int nh_grp_res_idle_timer;
    long unsigned int nh_grp_res_unbalanced_timer;
    bool nh_grp_res_has_num_buckets;
    bool nh_grp_res_has_idle_timer;
    bool nh_grp_res_has_unbalanced_timer;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    u16 nh_grp_res_num_buckets;
    long unsigned int nh_grp_res_idle_timer;
    long unsigned int nh_grp_res_unbalanced_timer;
    bool nh_grp_res_has_num_buckets;
    bool nh_grp_res_has_idle_timer;
    bool nh_grp_res_has_unbalanced_timer;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    u16 nh_grp_res_num_buckets;
    long unsigned int nh_grp_res_idle_timer;
    long unsigned int nh_grp_res_unbalanced_timer;
    bool nh_grp_res_has_num_buckets;
    bool nh_grp_res_has_idle_timer;
    bool nh_grp_res_has_unbalanced_timer;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    u16 nh_grp_res_num_buckets;
    long unsigned int nh_grp_res_idle_timer;
    long unsigned int nh_grp_res_unbalanced_timer;
    bool nh_grp_res_has_num_buckets;
    bool nh_grp_res_has_idle_timer;
    bool nh_grp_res_has_unbalanced_timer;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u8 nh_fdb;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    u16 nh_grp_res_num_buckets;
    long unsigned int nh_grp_res_idle_timer;
    long unsigned int nh_grp_res_unbalanced_timer;
    bool nh_grp_res_has_num_buckets;
    bool nh_grp_res_has_idle_timer;
    bool nh_grp_res_has_unbalanced_timer;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
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
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
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
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct nh_config {
    u32 nh_id;
    u8 nh_family;
    u8 nh_protocol;
    u8 nh_blackhole;
    u32 nh_flags;
    int nh_ifindex;
    struct net_device * dev;
    union (anon) gw;
    struct nlattr * nh_grp;
    u16 nh_grp_type;
    struct nlattr * nh_encap;
    u16 nh_encap_type;
    u32 nlflags;
    struct nl_info nlinfo;
}
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 nh_fdb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 nh_grp_res_num_buckets</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nh_grp_res_idle_timer</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int nh_grp_res_unbalanced_timer</code>
</li>
<li>
<b>Field added. </b>
<code>bool nh_grp_res_has_num_buckets</code>
</li>
<li>
<b>Field added. </b>
<code>bool nh_grp_res_has_idle_timer</code>
</li>
<li>
<b>Field added. </b>
<code>bool nh_grp_res_has_unbalanced_timer</code>
</li>
</ul>
</details>
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
