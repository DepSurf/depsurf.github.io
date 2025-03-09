# Struct: <code>atm_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    atomic_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    atomic_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    refcount_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    refcount_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    refcount_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    atomic_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
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
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>refcount_t refcnt</code>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct atm_dev {
    const struct atmdev_ops * ops;
    const struct atmphy_ops * phy;
    const char * type;
    int number;
    void * dev_data;
    void * phy_data;
    long unsigned int flags;
    struct list_head local;
    struct list_head lecs;
    unsigned char[6] esi;
    struct atm_cirange ci_range;
    struct k_atm_dev_stats stats;
    char signal;
    int link_rate;
    refcount_t refcnt;
    spinlock_t lock;
    struct proc_dir_entry * proc_entry;
    char * proc_name;
    struct device class_dev;
    struct list_head dev_list;
}
```
</details>
</li>
</ul>
