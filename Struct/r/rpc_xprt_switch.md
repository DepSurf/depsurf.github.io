# Struct: <code>rpc_xprt_switch</code>

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
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_id;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    unsigned int xps_nunique_destaddr_xprts;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct rpc_sysfs_xprt_switch * xps_sysfs;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_id;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    unsigned int xps_nunique_destaddr_xprts;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct rpc_sysfs_xprt_switch * xps_sysfs;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_id;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    unsigned int xps_nunique_destaddr_xprts;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct rpc_sysfs_xprt_switch * xps_sysfs;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_id;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    unsigned int xps_nunique_destaddr_xprts;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct rpc_sysfs_xprt_switch * xps_sysfs;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_id;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    unsigned int xps_nunique_destaddr_xprts;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct rpc_sysfs_xprt_switch * xps_sysfs;
    struct callback_head xps_rcu;
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
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
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
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
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
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int xps_nactive</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t xps_queuelen</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_xprt_switch {
    spinlock_t xps_lock;
    struct kref xps_kref;
    unsigned int xps_nxprts;
    unsigned int xps_nactive;
    atomic_long_t xps_queuelen;
    struct list_head xps_xprt_list;
    struct net * xps_net;
    const struct rpc_xprt_iter_ops * xps_iter_ops;
    struct callback_head xps_rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int xps_id</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int xps_nunique_destaddr_xprts</code>
</li>
<li>
<b>Field added. </b>
<code>struct rpc_sysfs_xprt_switch * xps_sysfs</code>
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
