# Struct: <code>rtnl_af_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *, struct netlink_ext_ack *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *, struct netlink_ext_ack *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *, struct netlink_ext_ack *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *, struct netlink_ext_ack *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *, struct netlink_ext_ack *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
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
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
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
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtnl_af_ops {
    struct list_head list;
    int family;
    int (*)(struct sk_buff *, const struct net_device *, u32) fill_link_af;
    size_t (*)(const struct net_device *, u32) get_link_af_size;
    int (*)(const struct net_device *, const struct nlattr *) validate_link_af;
    int (*)(struct net_device *, const struct nlattr *) set_link_af;
    int (*)(struct sk_buff *, const struct net_device *) fill_stats_af;
    size_t (*)(const struct net_device *) get_stats_af_size;
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
<code>int (*)(struct sk_buff *, const struct net_device *) fill_stats_af</code>
</li>
<li>
<b>Field added. </b>
<code>size_t (*)(const struct net_device *) get_stats_af_size</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, const struct nlattr *) set_link_af</code> ➡️ <code>int (*)(struct net_device *, const struct nlattr *, struct netlink_ext_ack *) set_link_af</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct net_device *, const struct nlattr *) validate_link_af</code> ➡️ <code>int (*)(const struct net_device *, const struct nlattr *, struct netlink_ext_ack *) validate_link_af</code>
</li>
</ul>
</details>
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
