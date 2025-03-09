# Struct: <code>nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct module * module;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct mutex reconfig_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct list_head poison_list;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct list_head poison_list;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct list_head poison_list;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    spinlock_t poison_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t probe_wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
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
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
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
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
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
<code>struct list_head poison_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mapping_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module * module</code>
</li>
</ul>
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
<b>Field added. </b>
<code>spinlock_t poison_lock</code>
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
<code>struct badrange badrange</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head poison_list</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t poison_lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<code>wait_queue_head_t wait</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t ioctl_active</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t probe_wait</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvdimm_bus {
    struct nvdimm_bus_descriptor * nd_desc;
    wait_queue_head_t wait;
    struct list_head list;
    struct device dev;
    int id;
    int probe_active;
    atomic_t ioctl_active;
    struct list_head mapping_list;
    struct mutex reconfig_mutex;
    struct badrange badrange;
}
```
</details>
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
