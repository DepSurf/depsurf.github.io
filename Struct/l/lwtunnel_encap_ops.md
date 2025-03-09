# Struct: <code>lwtunnel_encap_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net_device *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *) build_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net_device *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *) build_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net_device *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
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
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
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
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lwtunnel_encap_ops {
    int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state;
    void (*)(struct lwtunnel_state *) destroy_state;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    int (*)(struct sk_buff *) input;
    int (*)(struct sk_buff *, struct lwtunnel_state *) fill_encap;
    int (*)(struct lwtunnel_state *) get_encap_size;
    int (*)(struct lwtunnel_state *, struct lwtunnel_state *) cmp_encap;
    int (*)(struct sk_buff *) xmit;
    struct module * owner;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct lwtunnel_state *) destroy_state</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *) xmit</code>
</li>
<li>
<b>Field added. </b>
<code>struct module * owner</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net_device *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *) build_state</code> ➡️ <code>int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state</code> ➡️ <code>int (*)(struct net *, struct nlattr *, unsigned int, const void *, struct lwtunnel_state * *, struct netlink_ext_ack *) build_state</code>
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
