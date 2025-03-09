# Struct: <code>xfrm_policy_afinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    short unsigned int family;
    struct dst_ops * dst_ops;
    void (*)(struct net *) garbage_collect;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    short unsigned int family;
    struct dst_ops * dst_ops;
    void (*)(struct net *) garbage_collect;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    short unsigned int family;
    struct dst_ops * dst_ops;
    void (*)(struct net *) garbage_collect;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    void (*)(struct sk_buff *, struct flowi *, int) decode_session;
    int (*)(const struct flowi *) get_tos;
    int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
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
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
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
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_policy_afinfo {
    struct dst_ops * dst_ops;
    struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup;
    int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr;
    int (*)(struct xfrm_dst *, struct net_device *, const struct flowi *) fill_dst;
    struct dst_entry * (*)(struct net *, struct dst_entry *) blackhole_route;
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
<b>Field removed. </b>
<code>short unsigned int family</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net *) garbage_collect</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *) dst_lookup</code> ➡️ <code>struct dst_entry * (*)(struct net *, int, int, const xfrm_address_t *, const xfrm_address_t *, u32) dst_lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *) get_saddr</code> ➡️ <code>int (*)(struct net *, int, xfrm_address_t *, xfrm_address_t *, u32) get_saddr</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>void (*)(struct sk_buff *, struct flowi *, int) decode_session</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(const struct flowi *) get_tos</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct xfrm_dst *, struct dst_entry *, int) init_path</code>
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
