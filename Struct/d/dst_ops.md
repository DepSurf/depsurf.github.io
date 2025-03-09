# Struct: <code>dst_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    void (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    void (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
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
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
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
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dst_ops {
    short unsigned int family;
    unsigned int gc_thresh;
    int (*)(struct dst_ops *) gc;
    struct dst_entry * (*)(struct dst_entry *, __u32) check;
    unsigned int (*)(const struct dst_entry *) default_advmss;
    unsigned int (*)(const struct dst_entry *) mtu;
    u32 * (*)(struct dst_entry *, long unsigned int) cow_metrics;
    void (*)(struct dst_entry *) destroy;
    void (*)(struct dst_entry *, struct net_device *, int) ifdown;
    struct dst_entry * (*)(struct dst_entry *) negative_advice;
    void (*)(struct sk_buff *) link_failure;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu;
    void (*)(struct dst_entry *, struct sock *, struct sk_buff *) redirect;
    int (*)(struct net *, struct sock *, struct sk_buff *) local_out;
    struct neighbour * (*)(const struct dst_entry *, struct sk_buff *, const void *) neigh_lookup;
    void (*)(const struct dst_entry *, const void *) confirm_neigh;
    struct kmem_cache * kmem_cachep;
    struct percpu_counter pcpuc_entries;
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
<code>void (*)(const struct dst_entry *, const void *) confirm_neigh</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32) update_pmtu</code> ➡️ <code>void (*)(struct dst_entry *, struct sock *, struct sk_buff *, u32, bool) update_pmtu</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dst_ops *) gc</code> ➡️ <code>void (*)(struct dst_ops *) gc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct dst_entry *, struct net_device *, int) ifdown</code> ➡️ <code>void (*)(struct dst_entry *, struct net_device *) ifdown</code>
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
