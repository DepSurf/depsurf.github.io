# Struct: <code>rproc</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    bool autonomous;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * clean_table;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * clean_table;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * clean_table;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    bool sysfs_read_only;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * clean_table;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    bool sysfs_read_only;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
    long unsigned int[1] features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * clean_table;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    bool sysfs_read_only;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
    long unsigned int[1] features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    const char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    enum rproc_dump_mechanism dump_conf;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u64 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * clean_table;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    bool sysfs_read_only;
    struct list_head dump_segments;
    int nb_vdev;
    u8 elf_class;
    u16 elf_machine;
    struct cdev cdev;
    bool cdev_put_on_release;
    long unsigned int[1] features;
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
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 elf_class</code>
</li>
<li>
<b>Field added. </b>
<code>u16 elf_machine</code>
</li>
<li>
<b>Field type changed. </b>
<code>char * firmware</code> ➡️ <code>const char * firmware</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 bootaddr</code> ➡️ <code>u64 bootaddr</code>
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
<code>enum rproc_dump_mechanism dump_conf</code>
</li>
<li>
<b>Field added. </b>
<code>bool autonomous</code>
</li>
<li>
<b>Field added. </b>
<code>struct cdev cdev</code>
</li>
<li>
<b>Field added. </b>
<code>bool cdev_put_on_release</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct resource_table * clean_table</code>
</li>
<li>
<b>Field removed. </b>
<code>bool autonomous</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool sysfs_read_only</code>
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
<code>long unsigned int[1] features</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct rproc {
    struct list_head node;
    struct iommu_domain * domain;
    const char * name;
    char * firmware;
    void * priv;
    struct rproc_ops * ops;
    struct device dev;
    atomic_t power;
    unsigned int state;
    struct mutex lock;
    struct dentry * dbg_dir;
    struct list_head traces;
    int num_traces;
    struct list_head carveouts;
    struct list_head mappings;
    u32 bootaddr;
    struct list_head rvdevs;
    struct list_head subdevs;
    struct idr notifyids;
    int index;
    struct work_struct crash_handler;
    unsigned int crash_cnt;
    bool recovery_disabled;
    int max_notifyid;
    struct resource_table * table_ptr;
    struct resource_table * cached_table;
    size_t table_sz;
    bool has_iommu;
    bool auto_boot;
    struct list_head dump_segments;
    int nb_vdev;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
