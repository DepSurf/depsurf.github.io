# Struct: <code>devlink</code>

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
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct devlink_dpipe_headers * dpipe_headers;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct devlink_dpipe_headers * dpipe_headers;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct devlink_dpipe_headers * dpipe_headers;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct devlink_dpipe_headers * dpipe_headers;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    const struct devlink_ops * ops;
    struct xarray snapshot_ids;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    u8 registered;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    const struct devlink_ops * ops;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    u8 registered;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    const struct devlink_ops * ops;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    u8 registered;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    u32 index;
    struct list_head port_list;
    struct list_head rate_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    const struct devlink_ops * ops;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    refcount_t refcount;
    struct completion comp;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    u32 index;
    struct list_head port_list;
    struct list_head rate_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    struct list_head linecard_list;
    struct mutex linecards_lock;
    const struct devlink_ops * ops;
    u64 features;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    refcount_t refcount;
    struct completion comp;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    u32 index;
    struct xarray ports;
    struct list_head rate_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    struct list_head linecard_list;
    struct mutex linecards_lock;
    const struct devlink_ops * ops;
    u64 features;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    struct lock_class_key lock_key;
    u8 reload_failed;
    refcount_t refcount;
    struct completion comp;
    struct callback_head rcu;
    struct notifier_block netdevice_nb;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    u32 index;
    struct xarray ports;
    struct list_head rate_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct xarray params;
    struct list_head region_list;
    struct list_head reporter_list;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    struct list_head linecard_list;
    const struct devlink_ops * ops;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    struct lock_class_key lock_key;
    u8 reload_failed;
    refcount_t refcount;
    struct rcu_work rwork;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devlink {
    u32 index;
    struct xarray ports;
    struct list_head rate_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct xarray params;
    struct list_head region_list;
    struct list_head reporter_list;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    struct list_head trap_policer_list;
    struct list_head linecard_list;
    const struct devlink_ops * ops;
    struct xarray snapshot_ids;
    struct devlink_dev_stats stats;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    struct lock_class_key lock_key;
    u8 reload_failed;
    refcount_t refcount;
    struct rcu_work rwork;
    struct devlink_rel * rel;
    struct xarray nested_rels;
    char[0] priv;
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
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
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
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct list_head resource_list;
    struct list_head param_list;
    struct list_head region_list;
    u32 snapshot_id;
    struct list_head reporter_list;
    struct mutex reporters_lock;
    struct devlink_dpipe_headers * dpipe_headers;
    struct list_head trap_list;
    struct list_head trap_group_list;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    struct mutex lock;
    u8 reload_failed;
    u8 reload_enabled;
    char[0] priv;
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
struct devlink {
    struct list_head list;
    struct list_head port_list;
    struct list_head sb_list;
    struct list_head dpipe_table_list;
    struct devlink_dpipe_headers * dpipe_headers;
    const struct devlink_ops * ops;
    struct device * dev;
    possible_net_t _net;
    char[0] priv;
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
<code>struct list_head resource_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex lock</code>
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
<code>struct list_head param_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head region_list</code>
</li>
<li>
<b>Field added. </b>
<code>u32 snapshot_id</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head trap_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head trap_group_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reload_failed</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reload_enabled</code>
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
<code>struct list_head trap_policer_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray snapshot_ids</code>
</li>
<li>
<b>Field added. </b>
<code>u8 registered</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 snapshot_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct devlink_dev_stats stats</code>
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
<code>u32 index</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rate_list</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t refcount</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion comp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 registered</code>
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
<code>struct list_head linecard_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex linecards_lock</code>
</li>
<li>
<b>Field added. </b>
<code>u64 features</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 reload_enabled</code>
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
<code>struct xarray ports</code>
</li>
<li>
<b>Field added. </b>
<code>struct lock_class_key lock_key</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block netdevice_nb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head port_list</code>
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
<code>struct xarray params</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcu_work rwork</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head param_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex reporters_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex linecards_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 features</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion comp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block netdevice_nb</code>
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
<code>struct devlink_rel * rel</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray nested_rels</code>
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
