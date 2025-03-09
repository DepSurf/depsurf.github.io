# Struct: <code>tc_action_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    struct tcf_hashinfo * hinfo;
    char[16] kind;
    __u32 type;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *, int) cleanup;
    int (*)(struct tc_action *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action *, int, int) init;
    int (*)(struct sk_buff *, struct netlink_callback *, int, struct tc_action *) walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    __u32 type;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *, int) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *) walk;
    void (*)(struct tc_action *, u64, u32, u64) stats_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    __u32 type;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *, int) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *) walk;
    void (*)(struct tc_action *, u64, u32, u64) stats_update;
    int (*)(const struct tc_action *, struct net *, struct net_device * *) get_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    __u32 type;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *, int) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *) walk;
    void (*)(struct tc_action *, u64, u32, u64) stats_update;
    int (*)(const struct tc_action *, struct net *, struct net_device * *) get_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    __u32 type;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *, int) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *) walk;
    void (*)(struct tc_action *, u64, u32, u64) stats_update;
    struct net_device * (*)(const struct tc_action *) get_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    __u32 type;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32, struct netlink_ext_ack *) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *) get_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    __u32 type;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *) get_dev;
    void (*)(struct net_device *) put_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *) get_dev;
    void (*)(struct net_device *) put_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
    int (*)(struct tc_action *, void *, u32 *, bool, struct netlink_ext_ack *) offload_act_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    unsigned int net_id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
    int (*)(struct tc_action *, void *, u32 *, bool, struct netlink_ext_ack *) offload_act_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    unsigned int net_id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
    int (*)(struct tc_action *, void *, u32 *, bool, struct netlink_ext_ack *) offload_act_setup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    unsigned int net_id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, struct tcf_proto *, u32, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
    int (*)(struct tc_action *, void *, u32 *, bool, struct netlink_ext_ack *) offload_act_setup;
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
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
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
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tc_action_ops {
    struct list_head head;
    char[16] kind;
    enum tca_id id;
    size_t size;
    struct module * owner;
    int (*)(struct sk_buff *, const struct tc_action *, struct tcf_result *) act;
    int (*)(struct sk_buff *, struct tc_action *, int, int) dump;
    void (*)(struct tc_action *) cleanup;
    int (*)(struct net *, struct tc_action * *, u32) lookup;
    int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init;
    int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk;
    void (*)(struct tc_action *, u64, u32, u64, bool) stats_update;
    size_t (*)(const struct tc_action *) get_fill_size;
    struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev;
    struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group;
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
<code>size_t size</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct tc_action *, u64, u32, u64) stats_update</code>
</li>
<li>
<b>Field removed. </b>
<code>struct tcf_hashinfo * hinfo</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct tc_action *, u32) lookup</code> ➡️ <code>int (*)(struct net *, struct tc_action * *, u32) lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action *, int, int) init</code> ➡️ <code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int) init</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sk_buff *, struct netlink_callback *, int, struct tc_action *) walk</code> ➡️ <code>int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *) walk</code>
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
<code>int (*)(const struct tc_action *, struct net *, struct net_device * *) get_dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct tc_action *, struct net *, struct net_device * *) get_dev</code> ➡️ <code>struct net_device * (*)(const struct tc_action *) get_dev</code>
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
<code>size_t (*)(const struct tc_action *) get_fill_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tc_action *, int) cleanup</code> ➡️ <code>void (*)(struct tc_action *) cleanup</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct tc_action * *, u32) lookup</code> ➡️ <code>int (*)(struct net *, struct tc_action * *, u32, struct netlink_ext_ack *) lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int) init</code> ➡️ <code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, struct netlink_ext_ack *) init</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *) walk</code> ➡️ <code>int (*)(struct net *, struct sk_buff *, struct netlink_callback *, int, const struct tc_action_ops *, struct netlink_ext_ack *) walk</code>
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
<code>void (*)(struct net_device *) put_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct tc_action * *, u32, struct netlink_ext_ack *) lookup</code> ➡️ <code>int (*)(struct net *, struct tc_action * *, u32) lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, struct netlink_ext_ack *) init</code> ➡️ <code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct netlink_ext_ack *) init</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tc_action *, u64, u32, u64) stats_update</code> ➡️ <code>void (*)(struct tc_action *, u64, u32, u64, bool) stats_update</code>
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
<code>enum tca_id id</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32 type</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct netlink_ext_ack *) init</code> ➡️ <code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init</code>
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
<code>struct psample_group * (*)(const struct tc_action *, tc_action_priv_destructor *) get_psample_group</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct net_device *) put_dev</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct net_device * (*)(const struct tc_action *) get_dev</code> ➡️ <code>struct net_device * (*)(const struct tc_action *, tc_action_priv_destructor *) get_dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, struct netlink_ext_ack *) init</code> ➡️ <code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, u32, struct netlink_ext_ack *) init</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct tc_action *, u64, u32, u64, bool) stats_update</code> ➡️ <code>void (*)(struct tc_action *, u64, u64, u64, u64, bool) stats_update</code>
</li>
</ul>
</details>
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
<code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, int, int, bool, struct tcf_proto *, u32, struct netlink_ext_ack *) init</code> ➡️ <code>int (*)(struct net *, struct nlattr *, struct nlattr *, struct tc_action * *, struct tcf_proto *, u32, struct netlink_ext_ack *) init</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct tc_action *, void *, u32 *, bool, struct netlink_ext_ack *) offload_act_setup</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int net_id</code>
</li>
</ul>
</details>
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
