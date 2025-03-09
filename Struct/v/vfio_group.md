# Struct: <code>vfio_group</code>

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
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    unsigned int dev_counter;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    unsigned int dev_counter;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    unsigned int dev_counter;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    unsigned int dev_counter;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct device dev;
    struct cdev cdev;
    refcount_t users;
    unsigned int container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct list_head vfio_next;
    struct list_head container_next;
    enum vfio_group_type type;
    unsigned int dev_counter;
    struct rw_semaphore group_rwsem;
    struct kvm * kvm;
    struct file * opened_file;
    struct blocking_notifier_head notifier;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
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
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
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
<code>unsigned int dev_counter</code>
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
<code>struct kvm * kvm</code> ➡️ <code>struct kvm * kvm</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<code>struct cdev cdev</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t users</code>
</li>
<li>
<b>Field added. </b>
<code>enum vfio_group_type type</code>
</li>
<li>
<b>Field added. </b>
<code>struct rw_semaphore group_rwsem</code>
</li>
<li>
<b>Field added. </b>
<code>struct file * opened_file</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kref kref</code>
</li>
<li>
<b>Field removed. </b>
<code>int minor</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block nb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head unbound_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex unbound_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t opened</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t container_q</code>
</li>
<li>
<b>Field removed. </b>
<code>bool noiommu</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t container_users</code> ➡️ <code>unsigned int container_users</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct device * dev</code> ➡️ <code>struct device dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct vfio_group {
    struct device dev;
    struct cdev cdev;
    refcount_t users;
    unsigned int container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct list_head vfio_next;
    struct list_head container_next;
    enum vfio_group_type type;
    unsigned int dev_counter;
    struct rw_semaphore group_rwsem;
    struct kvm * kvm;
    struct file * opened_file;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct kvm * kvm</code> ➡️ <code>struct kvm * kvm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct vfio_group {
    struct kref kref;
    int minor;
    atomic_t container_users;
    struct iommu_group * iommu_group;
    struct vfio_container * container;
    struct list_head device_list;
    struct mutex device_lock;
    struct device * dev;
    struct notifier_block nb;
    struct list_head vfio_next;
    struct list_head container_next;
    struct list_head unbound_list;
    struct mutex unbound_lock;
    atomic_t opened;
    wait_queue_head_t container_q;
    bool noiommu;
    struct kvm * kvm;
    struct blocking_notifier_head notifier;
}
```
</details>
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
