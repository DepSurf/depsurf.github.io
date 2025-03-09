# Struct: <code>bus_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    struct device_attribute * dev_attrs;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    struct device_attribute * dev_attrs;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    struct device_attribute * dev_attrs;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool force_dma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    void (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    void (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    void (*)(struct device *) dma_cleanup;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    void (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    void (*)(struct device *) dma_cleanup;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(const struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    void (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    void (*)(struct device *) dma_cleanup;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(const struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    void (*)(struct device *) sync_state;
    void (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    void (*)(struct device *) dma_cleanup;
    const struct dev_pm_ops * pm;
    bool need_parent_lock;
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
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
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
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bus_type {
    const char * name;
    const char * dev_name;
    struct device * dev_root;
    const struct attribute_group * * bus_groups;
    const struct attribute_group * * dev_groups;
    const struct attribute_group * * drv_groups;
    int (*)(struct device *, struct device_driver *) match;
    int (*)(struct device *, struct kobj_uevent_env *) uevent;
    int (*)(struct device *) probe;
    int (*)(struct device *) remove;
    void (*)(struct device *) shutdown;
    int (*)(struct device *) online;
    int (*)(struct device *) offline;
    int (*)(struct device *, pm_message_t) suspend;
    int (*)(struct device *) resume;
    int (*)(struct device *) num_vf;
    int (*)(struct device *) dma_configure;
    const struct dev_pm_ops * pm;
    const struct iommu_ops * iommu_ops;
    struct subsys_private * p;
    struct lock_class_key lock_key;
    bool need_parent_lock;
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
<b>Field added. </b>
<code>int (*)(struct device *) num_vf</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device_attribute * dev_attrs</code>
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
<code>bool force_dma</code>
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
<code>int (*)(struct device *) dma_configure</code>
</li>
<li>
<b>Field added. </b>
<code>bool need_parent_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool force_dma</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct device *) sync_state</code>
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
<code>int (*)(struct device *) remove</code> ➡️ <code>void (*)(struct device *) remove</code>
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
<code>void (*)(struct device *) dma_cleanup</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct device * dev_root</code>
</li>
<li>
<b>Field removed. </b>
<code>struct subsys_private * p</code>
</li>
<li>
<b>Field removed. </b>
<code>struct lock_class_key lock_key</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct device *, struct kobj_uevent_env *) uevent</code> ➡️ <code>int (*)(const struct device *, struct kobj_uevent_env *) uevent</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const struct iommu_ops * iommu_ops</code>
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
