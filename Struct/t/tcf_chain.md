# Struct: <code>tcf_chain</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct tcf_proto * filter_chain;
    struct tcf_proto * * p_filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct tcf_proto * filter_chain;
    tcf_chain_head_change_t * chain_head_change;
    void * chain_head_change_priv;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct tcf_proto * filter_chain;
    struct list_head filter_chain_list;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
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
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
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
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcf_chain {
    struct mutex filter_chain_lock;
    struct tcf_proto * filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
    unsigned int action_refcnt;
    bool explicitly_created;
    bool flushing;
    const struct tcf_proto_ops * tmplt_ops;
    void * tmplt_priv;
    struct callback_head rcu;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct tcf_chain {
    struct tcf_proto * filter_chain;
    struct tcf_proto * * p_filter_chain;
    struct list_head list;
    struct tcf_block * block;
    u32 index;
    unsigned int refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>tcf_chain_head_change_t * chain_head_change</code>
</li>
<li>
<b>Field added. </b>
<code>void * chain_head_change_priv</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tcf_proto * * p_filter_chain</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head filter_chain_list</code>
</li>
<li>
<b>Field removed. </b>
<code>tcf_chain_head_change_t * chain_head_change</code>
</li>
<li>
<b>Field removed. </b>
<code>void * chain_head_change_priv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int action_refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>bool explicitly_created</code>
</li>
<li>
<b>Field added. </b>
<code>const struct tcf_proto_ops * tmplt_ops</code>
</li>
<li>
<b>Field added. </b>
<code>void * tmplt_priv</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head filter_chain_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex filter_chain_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool flushing</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
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
