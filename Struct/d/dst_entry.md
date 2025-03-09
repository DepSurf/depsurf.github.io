# Struct: <code>dst_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct callback_head callback_head;
    struct dst_entry * child;
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct dst_entry * path;
    struct dst_entry * from;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short unsigned int pending_confirm;
    short int error;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    __u32 tclassid;
    struct lwtunnel_state * lwtstate;
    long int[1] __pad_to_align_refcnt;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct dst_entry * next;
    struct rtable * rt_next;
    struct rt6_info * rt6_next;
    struct dn_route * dn_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct callback_head callback_head;
    struct dst_entry * child;
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct dst_entry * path;
    struct dst_entry * from;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short unsigned int pending_confirm;
    short int error;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    __u32 tclassid;
    long int[2] __pad_to_align_refcnt;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct dst_entry * next;
    struct rtable * rt_next;
    struct rt6_info * rt6_next;
    struct dn_route * dn_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct callback_head callback_head;
    struct dst_entry * child;
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct dst_entry * path;
    struct dst_entry * from;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short unsigned int pending_confirm;
    short int error;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    __u32 tclassid;
    long int[2] __pad_to_align_refcnt;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct dst_entry * next;
    struct rtable * rt_next;
    struct rt6_info * rt6_next;
    struct dn_route * dn_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct callback_head callback_head;
    struct dst_entry * child;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct dst_entry * path;
    struct dst_entry * from;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int error;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    short unsigned int __pad3;
    __u32 tclassid;
    long int[2] __pad_to_align_refcnt;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct dst_entry * next;
    struct rtable * rt_next;
    struct rt6_info * rt6_next;
    struct dn_route * dn_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct callback_head callback_head;
    struct dst_entry * child;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct dst_entry * path;
    struct dst_entry * from;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int error;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    short unsigned int __pad3;
    __u32 tclassid;
    long int[2] __pad_to_align_refcnt;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct dst_entry * next;
    struct rtable * rt_next;
    struct rt6_info * rt6_next;
    struct dn_route * dn_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
    netdevice_tracker dev_tracker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
    netdevice_tracker dev_tracker;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    rcuref_t __rcuref;
    int __use;
    long unsigned int lastuse;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
    netdevice_tracker dev_tracker;
    struct list_head rt_uncached;
    struct uncached_list * rt_uncached_list;
    struct lwtunnel_state * lwtstate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    rcuref_t __rcuref;
    int __use;
    long unsigned int lastuse;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
    netdevice_tracker dev_tracker;
    struct list_head rt_uncached;
    struct uncached_list * rt_uncached_list;
    struct lwtunnel_state * lwtstate;
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
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
    atomic_t __refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
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
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dst_entry {
    struct net_device * dev;
    struct dst_ops * ops;
    long unsigned int _metrics;
    long unsigned int expires;
    struct xfrm_state * xfrm;
    int (*)(struct sk_buff *) input;
    int (*)(struct net *, struct sock *, struct sk_buff *) output;
    short unsigned int flags;
    short int obsolete;
    short unsigned int header_len;
    short unsigned int trailer_len;
    atomic_t __refcnt;
    int __use;
    long unsigned int lastuse;
    struct lwtunnel_state * lwtstate;
    struct callback_head callback_head;
    short int error;
    short int __pad;
    __u32 tclassid;
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
<b>Field type changed. </b>
<code>long int[1] __pad_to_align_refcnt</code> ➡️ <code>long int[2] __pad_to_align_refcnt</code>
</li>
</ul>
</details>
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
<code>short unsigned int __pad3</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int pending_confirm</code>
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
<code>short int __pad</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dst_entry * child</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dst_entry * path</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dst_entry * from</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int __pad3</code>
</li>
<li>
<b>Field removed. </b>
<code>long int[2] __pad_to_align_refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dst_entry * next</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rtable * rt_next</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rt6_info * rt6_next</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dn_route * dn_next</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>netdevice_tracker dev_tracker</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>rcuref_t __rcuref</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rt_uncached</code>
</li>
<li>
<b>Field added. </b>
<code>struct uncached_list * rt_uncached_list</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t __refcnt</code>
</li>
</ul>
</details>
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
