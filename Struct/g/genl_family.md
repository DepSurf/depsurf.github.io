# Struct: <code>genl_family</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    unsigned int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct list_head family_list;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    unsigned int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct list_head family_list;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    unsigned int mcgrp_offset;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_mcgrps;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    unsigned int mcgrp_offset;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_mcgrps;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    unsigned int mcgrp_offset;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_mcgrps;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    unsigned int mcgrp_offset;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_mcgrps;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_split_ops;
    u8 n_mcgrps;
    u8 resv_start_op;
    const struct nla_policy * policy;
    int (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_split_ops * split_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
    int id;
    unsigned int mcgrp_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_split_ops;
    u8 n_mcgrps;
    u8 resv_start_op;
    const struct nla_policy * policy;
    int (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_split_ops * split_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
    int id;
    unsigned int mcgrp_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct genl_family {
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    u8 netnsok;
    u8 parallel_ops;
    u8 n_ops;
    u8 n_small_ops;
    u8 n_split_ops;
    u8 n_mcgrps;
    u8 resv_start_op;
    const struct nla_policy * policy;
    int (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) post_doit;
    const struct genl_ops * ops;
    const struct genl_small_ops * small_ops;
    const struct genl_split_ops * split_ops;
    const struct genl_multicast_group * mcgrps;
    struct module * module;
    size_t sock_priv_size;
    void (*)(void *) sock_priv_init;
    void (*)(void *) sock_priv_destroy;
    int id;
    unsigned int mcgrp_offset;
    struct xarray * sock_privs;
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
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
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
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct genl_family {
    int id;
    unsigned int hdrsize;
    char[16] name;
    unsigned int version;
    unsigned int maxattr;
    bool netnsok;
    bool parallel_ops;
    const struct nla_policy * policy;
    int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit;
    void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit;
    int (*)(struct net *, int) mcast_bind;
    void (*)(struct net *, int) mcast_unbind;
    struct nlattr * * attrbuf;
    const struct genl_ops * ops;
    const struct genl_multicast_group * mcgrps;
    unsigned int n_ops;
    unsigned int n_mcgrps;
    unsigned int mcgrp_offset;
    struct module * module;
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
<b>Field removed. </b>
<code>struct list_head family_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int id</code> ➡️ <code>int id</code>
</li>
</ul>
</details>
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
<code>const struct nla_policy * policy</code>
</li>
</ul>
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
<b>Field removed. </b>
<code>int (*)(struct net *, int) mcast_bind</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net *, int) mcast_unbind</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nlattr * * attrbuf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 n_small_ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct genl_small_ops * small_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool netnsok</code> ➡️ <code>u8 netnsok</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool parallel_ops</code> ➡️ <code>u8 parallel_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int n_ops</code> ➡️ <code>u8 n_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int n_mcgrps</code> ➡️ <code>u8 n_mcgrps</code>
</li>
</ul>
</details>
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
<code>u8 n_split_ops</code>
</li>
<li>
<b>Field added. </b>
<code>u8 resv_start_op</code>
</li>
<li>
<b>Field added. </b>
<code>const struct genl_split_ops * split_ops</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) pre_doit</code> ➡️ <code>int (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) pre_doit</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(const struct genl_ops *, struct sk_buff *, struct genl_info *) post_doit</code> ➡️ <code>void (*)(const struct genl_split_ops *, struct sk_buff *, struct genl_info *) post_doit</code>
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
<code>size_t sock_priv_size</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *) sock_priv_init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *) sock_priv_destroy</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray * sock_privs</code>
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
