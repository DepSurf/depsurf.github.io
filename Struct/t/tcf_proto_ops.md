# Struct: <code>tcf_proto_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    bool (*)(struct tcf_proto *, bool) destroy;
    long unsigned int (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, long unsigned int *, bool) change;
    int (*)(struct tcf_proto *, long unsigned int) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    int (*)(struct net *, struct tcf_proto *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    bool (*)(struct tcf_proto *, bool) destroy;
    long unsigned int (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, long unsigned int *, bool) change;
    int (*)(struct tcf_proto *, long unsigned int) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    int (*)(struct net *, struct tcf_proto *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    bool (*)(struct tcf_proto *, bool) destroy;
    long unsigned int (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, long unsigned int *, bool) change;
    int (*)(struct tcf_proto *, long unsigned int) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    int (*)(struct net *, struct tcf_proto *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *) destroy;
    long unsigned int (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, long unsigned int *, bool) change;
    int (*)(struct tcf_proto *, long unsigned int, bool *) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    int (*)(struct net *, struct tcf_proto *, long unsigned int, struct sk_buff *, struct tcmsg *) dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool) change;
    int (*)(struct tcf_proto *, void *, bool *) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    void (*)(void *, u32, long unsigned int) bind_class;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *) dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, struct netlink_ext_ack *) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    void (*)(void *, u32, long unsigned int) bind_class;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *) dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, struct netlink_ext_ack *) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *) walk;
    int (*)(struct tcf_proto *, bool, tc_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(void *, u32, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(void *, u32, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, u32, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, u32, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, u32, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, u32, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    struct tcf_exts * (*)(const struct tcf_proto *, u32) get_exts;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, u32, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    void (*)(struct tcf_chain *, bool, flow_setup_cb_t *, void *) tmplt_reoffload;
    struct tcf_exts * (*)(const struct tcf_proto *, u32) get_exts;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
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
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
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
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcf_proto_ops {
    struct list_head head;
    char[16] kind;
    int (*)(struct sk_buff *, const struct tcf_proto *, struct tcf_result *) classify;
    int (*)(struct tcf_proto *) init;
    void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy;
    void * (*)(struct tcf_proto *, u32) get;
    void (*)(struct tcf_proto *, void *) put;
    int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change;
    int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete;
    bool (*)(struct tcf_proto *) delete_empty;
    void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk;
    int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload;
    void (*)(struct tcf_proto *, void *) hw_add;
    void (*)(struct tcf_proto *, void *) hw_del;
    void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class;
    void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create;
    void (*)(void *) tmplt_destroy;
    int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump;
    int (*)(struct sk_buff *, struct net *, void *) tmplt_dump;
    struct module * owner;
    int flags;
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
<b>Field type changed. </b>
<code>bool (*)(struct tcf_proto *, bool) destroy</code> ➡️ <code>void (*)(struct tcf_proto *) destroy</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tcf_proto *, long unsigned int) delete</code> ➡️ <code>int (*)(struct tcf_proto *, long unsigned int, bool *) delete</code>
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
<code>void (*)(void *, u32, long unsigned int) bind_class</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int (*)(struct tcf_proto *, u32) get</code> ➡️ <code>void * (*)(struct tcf_proto *, u32) get</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, long unsigned int *, bool) change</code> ➡️ <code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool) change</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tcf_proto *, long unsigned int, bool *) delete</code> ➡️ <code>int (*)(struct tcf_proto *, void *, bool *) delete</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct tcf_proto *, long unsigned int, struct sk_buff *, struct tcmsg *) dump</code> ➡️ <code>int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *) dump</code>
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
<code>void (*)(struct tcf_proto *) destroy</code> ➡️ <code>void (*)(struct tcf_proto *, struct netlink_ext_ack *) destroy</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool) change</code> ➡️ <code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, struct netlink_ext_ack *) change</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tcf_proto *, void *, bool *) delete</code> ➡️ <code>int (*)(struct tcf_proto *, void *, bool *, struct netlink_ext_ack *) delete</code>
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
<code>int (*)(struct tcf_proto *, bool, tc_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload</code>
</li>
<li>
<b>Field added. </b>
<code>void * (*)(struct net *, struct tcf_chain *, struct nlattr * *, struct netlink_ext_ack *) tmplt_create</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *) tmplt_destroy</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct net *, void *) tmplt_dump</code>
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
<code>void (*)(struct tcf_proto *, void *) put</code>
</li>
<li>
<b>Field added. </b>
<code>int flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tcf_proto *, struct netlink_ext_ack *) destroy</code> ➡️ <code>void (*)(struct tcf_proto *, bool, struct netlink_ext_ack *) destroy</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, struct netlink_ext_ack *) change</code> ➡️ <code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tcf_proto *, void *, bool *, struct netlink_ext_ack *) delete</code> ➡️ <code>int (*)(struct tcf_proto *, void *, bool *, bool, struct netlink_ext_ack *) delete</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tcf_proto *, struct tcf_walker *) walk</code> ➡️ <code>void (*)(struct tcf_proto *, struct tcf_walker *, bool) walk</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tcf_proto *, bool, tc_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload</code> ➡️ <code>int (*)(struct tcf_proto *, bool, flow_setup_cb_t *, void *, struct netlink_ext_ack *) reoffload</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *) dump</code> ➡️ <code>int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) dump</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct tcf_proto *) delete_empty</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct tcf_proto *, void *) hw_add</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct tcf_proto *, void *) hw_del</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(void *, u32, long unsigned int) bind_class</code> ➡️ <code>void (*)(void *, u32, long unsigned int, void *, long unsigned int) bind_class</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct net *, struct tcf_proto *, void *, struct sk_buff *, struct tcmsg *, bool) terse_dump</code>
</li>
</ul>
</details>
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
<b>Field type changed. </b>
<code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, bool, bool, struct netlink_ext_ack *) change</code> ➡️ <code>int (*)(struct net *, struct sk_buff *, struct tcf_proto *, long unsigned int, u32, struct nlattr * *, void * *, u32, struct netlink_ext_ack *) change</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct tcf_exts * (*)(const struct tcf_proto *, u32) get_exts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct tcf_chain *, bool, flow_setup_cb_t *, void *) tmplt_reoffload</code>
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
