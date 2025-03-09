# Struct: <code>Qdisc_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    int (*)(struct sk_buff *, struct Qdisc *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    unsigned int (*)(struct Qdisc *) drop;
    int (*)(struct Qdisc *, struct nlattr *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    void (*)(struct Qdisc *, unsigned int) change_real_num_tx;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    void (*)(struct Qdisc *, unsigned int) change_real_num_tx;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    void (*)(struct Qdisc *, unsigned int) change_real_num_tx;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    void (*)(struct Qdisc *, unsigned int) change_real_num_tx;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    void (*)(struct Qdisc *, unsigned int) change_real_num_tx;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
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
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
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
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct Qdisc_ops {
    struct Qdisc_ops * next;
    const struct Qdisc_class_ops * cl_ops;
    char[16] id;
    int priv_size;
    unsigned int static_flags;
    int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue;
    struct sk_buff * (*)(struct Qdisc *) dequeue;
    struct sk_buff * (*)(struct Qdisc *) peek;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init;
    void (*)(struct Qdisc *) reset;
    void (*)(struct Qdisc *) destroy;
    int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change;
    void (*)(struct Qdisc *) attach;
    int (*)(struct Qdisc *, unsigned int) change_tx_queue_len;
    int (*)(struct Qdisc *, struct sk_buff *) dump;
    int (*)(struct Qdisc *, struct gnet_dump *) dump_stats;
    void (*)(struct Qdisc *, u32) ingress_block_set;
    void (*)(struct Qdisc *, u32) egress_block_set;
    u32 (*)(struct Qdisc *) ingress_block_get;
    u32 (*)(struct Qdisc *) egress_block_get;
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int (*)(struct Qdisc *) drop</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sk_buff *, struct Qdisc *) enqueue</code> ➡️ <code>int (*)(struct sk_buff *, struct Qdisc *, struct sk_buff * *) enqueue</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int static_flags</code>
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
<code>int (*)(struct Qdisc *, unsigned int) change_tx_queue_len</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct Qdisc *, u32) ingress_block_set</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct Qdisc *, u32) egress_block_set</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct Qdisc *) ingress_block_get</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct Qdisc *) egress_block_get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct Qdisc *, struct nlattr *) init</code> ➡️ <code>int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) init</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct Qdisc *, struct nlattr *) change</code> ➡️ <code>int (*)(struct Qdisc *, struct nlattr *, struct netlink_ext_ack *) change</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct Qdisc *, unsigned int) change_real_num_tx</code>
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
