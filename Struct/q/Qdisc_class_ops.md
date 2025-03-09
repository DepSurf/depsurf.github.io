# Struct: <code>Qdisc_class_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) get;
    void (*)(struct Qdisc *, long unsigned int) put;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_proto * * (*)(struct Qdisc *, long unsigned int) tcf_chain;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) get;
    void (*)(struct Qdisc *, long unsigned int) put;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_proto * * (*)(struct Qdisc *, long unsigned int) tcf_chain;
    bool (*)(u32) tcf_cl_offload;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) get;
    void (*)(struct Qdisc *, long unsigned int) put;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_proto * * (*)(struct Qdisc *, long unsigned int) tcf_chain;
    bool (*)(u32) tcf_cl_offload;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) get;
    void (*)(struct Qdisc *, long unsigned int) put;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int) tcf_block;
    bool (*)(u32) tcf_cl_offload;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
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
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
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
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct Qdisc_class_ops {
    unsigned int flags;
    struct netdev_queue * (*)(struct Qdisc *, struct tcmsg *) select_queue;
    int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft;
    struct Qdisc * (*)(struct Qdisc *, long unsigned int) leaf;
    void (*)(struct Qdisc *, long unsigned int) qlen_notify;
    long unsigned int (*)(struct Qdisc *, u32) find;
    int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change;
    int (*)(struct Qdisc *, long unsigned int) delete;
    void (*)(struct Qdisc *, struct qdisc_walker *) walk;
    struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block;
    long unsigned int (*)(struct Qdisc *, long unsigned int, u32) bind_tcf;
    void (*)(struct Qdisc *, long unsigned int) unbind_tcf;
    int (*)(struct Qdisc *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct Qdisc *, long unsigned int, struct gnet_dump *) dump_stats;
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
<code>bool (*)(u32) tcf_cl_offload</code>
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
<code>struct tcf_block * (*)(struct Qdisc *, long unsigned int) tcf_block</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tcf_proto * * (*)(struct Qdisc *, long unsigned int) tcf_chain</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct Qdisc *, u32) find</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)(struct Qdisc *, u32) get</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct Qdisc *, long unsigned int) put</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(u32) tcf_cl_offload</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *) graft</code> ➡️ <code>int (*)(struct Qdisc *, long unsigned int, struct Qdisc *, struct Qdisc * *, struct netlink_ext_ack *) graft</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *) change</code> ➡️ <code>int (*)(struct Qdisc *, u32, u32, struct nlattr * *, long unsigned int *, struct netlink_ext_ack *) change</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct tcf_block * (*)(struct Qdisc *, long unsigned int) tcf_block</code> ➡️ <code>struct tcf_block * (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) tcf_block</code>
</li>
</ul>
</details>
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
<code>unsigned int flags</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct Qdisc *, long unsigned int) delete</code> ➡️ <code>int (*)(struct Qdisc *, long unsigned int, struct netlink_ext_ack *) delete</code>
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
