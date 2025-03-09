# Struct: <code>padata_instance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct notifier_block cpu_notifier;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct notifier_block cpu_notifier;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * wq;
    struct parallel_data * pd;
    struct padata_cpumask cpumask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node cpu_online_node;
    struct hlist_node cpu_dead_node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
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
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
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
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct padata_instance {
    struct hlist_node node;
    struct workqueue_struct * parallel_wq;
    struct workqueue_struct * serial_wq;
    struct list_head pslist;
    struct padata_cpumask cpumask;
    struct padata_cpumask rcpumask;
    cpumask_var_t omask;
    struct blocking_notifier_head cpumask_change_notifier;
    struct kobject kobj;
    struct mutex lock;
    u8 flags;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block cpu_notifier</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct workqueue_struct * parallel_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct workqueue_struct * serial_wq</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head pslist</code>
</li>
<li>
<b>Field added. </b>
<code>struct padata_cpumask rcpumask</code>
</li>
<li>
<b>Field added. </b>
<code>cpumask_var_t omask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct workqueue_struct * wq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct parallel_data * pd</code>
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
<code>struct hlist_node cpu_online_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node cpu_dead_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field removed. </b>
<code>cpumask_var_t omask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blocking_notifier_head cpumask_change_notifier</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct padata_cpumask rcpumask</code>
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
