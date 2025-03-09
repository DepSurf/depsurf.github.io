# Struct: <code>clk_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct clk_core * parent;
    const char * * parent_names;
    struct clk_core * * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
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
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
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
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device * dev</code>
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
<code>unsigned int protect_count</code>
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
<code>struct clk_duty duty</code>
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
<code>struct device_node * of_node</code>
</li>
<li>
<b>Field added. </b>
<code>bool rpm_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * * parent_names</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct clk_core * * parents</code> ➡️ <code>struct clk_parent_map * parents</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct clk_core {
    const char * name;
    const struct clk_ops * ops;
    struct clk_hw * hw;
    struct module * owner;
    struct device * dev;
    struct device_node * of_node;
    struct clk_core * parent;
    struct clk_parent_map * parents;
    u8 num_parents;
    u8 new_parent_index;
    long unsigned int rate;
    long unsigned int req_rate;
    long unsigned int new_rate;
    struct clk_core * new_parent;
    struct clk_core * new_child;
    long unsigned int flags;
    bool orphan;
    bool rpm_enabled;
    unsigned int enable_count;
    unsigned int prepare_count;
    unsigned int protect_count;
    long unsigned int min_rate;
    long unsigned int max_rate;
    long unsigned int accuracy;
    int phase;
    struct clk_duty duty;
    struct hlist_head children;
    struct hlist_node child_node;
    struct hlist_head clks;
    unsigned int notifier_count;
    struct dentry * dentry;
    struct hlist_node debug_node;
    struct kref ref;
}
```
</details>
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
