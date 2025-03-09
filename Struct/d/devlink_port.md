# Struct: <code>devlink_port</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    bool split;
    u32 split_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    bool split;
    u32 split_group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct list_head region_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct mutex reporters_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct list_head region_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct mutex reporters_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct list_head region_list;
    struct devlink * devlink;
    unsigned int index;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_rate * devlink_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct list_head region_list;
    struct devlink * devlink;
    unsigned int index;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_rate * devlink_rate;
    struct devlink_linecard * linecard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head region_list;
    struct devlink * devlink;
    unsigned int index;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    struct (anon) type_eth;
    struct (anon) type_ib;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    u8 registered;
    u8 initialized;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_rate * devlink_rate;
    struct devlink_linecard * linecard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head region_list;
    struct devlink * devlink;
    const struct devlink_port_ops * ops;
    unsigned int index;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    struct (anon) type_eth;
    struct (anon) type_ib;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    u8 registered;
    u8 initialized;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct devlink_rate * devlink_rate;
    struct devlink_linecard * linecard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head region_list;
    struct devlink * devlink;
    const struct devlink_port_ops * ops;
    unsigned int index;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    struct (anon) type_eth;
    struct (anon) type_ib;
    struct devlink_port_attrs attrs;
    u8 attrs_set;
    u8 switch_port;
    u8 registered;
    u8 initialized;
    struct delayed_work type_warn_dw;
    struct list_head reporter_list;
    struct devlink_rate * devlink_rate;
    struct devlink_linecard * linecard;
    u32 rel_index;
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
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
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
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink_port {
    struct list_head list;
    struct list_head param_list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    spinlock_t type_lock;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    struct devlink_port_attrs attrs;
    struct delayed_work type_warn_dw;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct devlink_port {
    struct list_head list;
    struct devlink * devlink;
    unsigned int index;
    bool registered;
    enum devlink_port_type type;
    enum devlink_port_type desired_type;
    void * type_dev;
    bool split;
    u32 split_group;
}
```
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
<code>struct devlink_port_attrs attrs</code>
</li>
<li>
<b>Field removed. </b>
<code>bool split</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 split_group</code>
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
<code>struct list_head param_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t type_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct delayed_work type_warn_dw</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head region_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 attrs_set</code>
</li>
<li>
<b>Field added. </b>
<code>u8 switch_port</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head reporter_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex reporters_lock</code>
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
<b>Field added. </b>
<code>struct devlink_rate * devlink_rate</code>
</li>
<li>
<b>Field removed. </b>
<code>bool registered</code>
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
<code>struct devlink_linecard * linecard</code>
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
<code>struct (anon) type_eth</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) type_ib</code>
</li>
<li>
<b>Field added. </b>
<code>u8 registered</code>
</li>
<li>
<b>Field added. </b>
<code>u8 initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head param_list</code>
</li>
<li>
<b>Field removed. </b>
<code>void * type_dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct devlink_port_ops * ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex reporters_lock</code>
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
<code>u32 rel_index</code>
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
