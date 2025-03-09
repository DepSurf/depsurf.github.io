# Struct: <code>fib_rule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    atomic_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    atomic_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    atomic_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
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
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
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
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fib_rule {
    struct list_head list;
    int iifindex;
    int oifindex;
    u32 mark;
    u32 mark_mask;
    u32 flags;
    u32 table;
    u8 action;
    u8 l3mdev;
    u8 proto;
    u8 ip_proto;
    u32 target;
    __be64 tun_id;
    struct fib_rule * ctarget;
    struct net * fr_net;
    refcount_t refcnt;
    u32 pref;
    int suppress_ifgroup;
    int suppress_prefixlen;
    char[16] iifname;
    char[16] oifname;
    struct fib_kuid_range uid_range;
    struct fib_rule_port_range sport_range;
    struct fib_rule_port_range dport_range;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 l3mdev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fib_kuid_range uid_range</code>
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
<code>atomic_t refcnt</code> ➡️ <code>refcount_t refcnt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 proto</code>
</li>
<li>
<b>Field added. </b>
<code>u8 ip_proto</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_rule_port_range sport_range</code>
</li>
<li>
<b>Field added. </b>
<code>struct fib_rule_port_range dport_range</code>
</li>
</ul>
</details>
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
