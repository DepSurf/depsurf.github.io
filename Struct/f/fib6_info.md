# Struct: <code>fib6_info</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    unsigned int fib6_nsiblings;
    atomic_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 exception_bucket_flushed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 unused;
    struct fib6_nh fib6_nh;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    unsigned int fib6_nsiblings;
    atomic_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
    long unsigned int last_probe;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 exception_bucket_flushed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 unused;
    struct fib6_nh fib6_nh;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 offload;
    u8 trap;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 offload;
    u8 trap;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 offload;
    u8 trap;
    u8 offload_failed;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 offload;
    u8 trap;
    u8 offload_failed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 offload;
    u8 trap;
    u8 offload_failed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 offload;
    u8 trap;
    u8 offload_failed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 offload;
    u8 trap;
    u8 offload_failed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 offload;
    u8 trap;
    u8 offload_failed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
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
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
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
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    struct list_head nh_list;
    unsigned int fib6_nsiblings;
    refcount_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 fib6_destroying;
    u8 unused;
    struct callback_head rcu;
    struct nexthop * nh;
    struct fib6_nh[0] fib6_nh;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct fib6_info {
    struct fib6_table * fib6_table;
    struct fib6_info * fib6_next;
    struct fib6_node * fib6_node;
    struct list_head fib6_siblings;
    unsigned int fib6_nsiblings;
    atomic_t fib6_ref;
    long unsigned int expires;
    struct dst_metrics * fib6_metrics;
    struct rt6key fib6_dst;
    u32 fib6_flags;
    struct rt6key fib6_src;
    struct rt6key fib6_prefsrc;
    struct rt6_info * * rt6i_pcpu;
    struct rt6_exception_bucket * rt6i_exception_bucket;
    u32 fib6_metric;
    u8 fib6_protocol;
    u8 fib6_type;
    u8 exception_bucket_flushed;
    u8 should_flush;
    u8 dst_nocount;
    u8 dst_nopolicy;
    u8 dst_host;
    u8 unused;
    struct fib6_nh fib6_nh;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int last_probe</code>
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
<code>struct list_head nh_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 fib6_destroying</code>
</li>
<li>
<b>Field added. </b>
<code>struct nexthop * nh</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rt6_info * * rt6i_pcpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rt6_exception_bucket * rt6i_exception_bucket</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_probe</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 exception_bucket_flushed</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t fib6_ref</code> ➡️ <code>refcount_t fib6_ref</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fib6_nh fib6_nh</code> ➡️ <code>struct fib6_nh[0] fib6_nh</code>
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
<b>Field added. </b>
<code>u8 offload</code>
</li>
<li>
<b>Field added. </b>
<code>u8 trap</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 dst_host</code>
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
<code>u8 offload_failed</code>
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
