# Struct: <code>l3mdev_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct rtable * (*)(const struct net_device *, const struct flowi4 *) l3mdev_get_rtable;
    int (*)(struct net_device *, struct flowi4 *) l3mdev_get_saddr;
    struct dst_entry * (*)(const struct net_device *, const struct flowi6 *) l3mdev_get_rt6_dst;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct rtable * (*)(const struct net_device *, const struct flowi4 *) l3mdev_get_rtable;
    int (*)(struct net_device *, struct flowi4 *) l3mdev_get_saddr;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_get_rt6_dst;
    int (*)(struct net_device *, const struct sock *, struct flowi6 *) l3mdev_get_saddr6;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
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
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
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
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct l3mdev_ops {
    u32 (*)(const struct net_device *) l3mdev_fib_table;
    struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv;
    struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out;
    struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup;
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
<code>struct sk_buff * (*)(struct net_device *, struct sk_buff *, u16) l3mdev_l3_rcv</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct net_device *, const struct sock *, struct flowi6 *) l3mdev_get_saddr6</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dst_entry * (*)(const struct net_device *, const struct flowi6 *) l3mdev_get_rt6_dst</code> ➡️ <code>struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_get_rt6_dst</code>
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
<code>struct sk_buff * (*)(struct net_device *, struct sock *, struct sk_buff *, u16) l3mdev_l3_out</code>
</li>
<li>
<b>Field added. </b>
<code>struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_link_scope_lookup</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rtable * (*)(const struct net_device *, const struct flowi4 *) l3mdev_get_rtable</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, struct flowi4 *) l3mdev_get_saddr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dst_entry * (*)(const struct net_device *, struct flowi6 *) l3mdev_get_rt6_dst</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct net_device *, const struct sock *, struct flowi6 *) l3mdev_get_saddr6</code>
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
