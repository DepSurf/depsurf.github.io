# Struct: <code>iommu_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
    struct list_head entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
    struct list_head entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
    struct list_head entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
    struct list_head entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * blocking_domain;
    struct iommu_domain * domain;
    struct list_head entry;
    unsigned int owner_cnt;
    void * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct xarray pasid_array;
    struct mutex mutex;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * blocking_domain;
    struct iommu_domain * domain;
    struct list_head entry;
    unsigned int owner_cnt;
    void * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct xarray pasid_array;
    struct mutex mutex;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * blocking_domain;
    struct iommu_domain * domain;
    struct list_head entry;
    unsigned int owner_cnt;
    void * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct xarray pasid_array;
    struct mutex mutex;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * blocking_domain;
    struct iommu_domain * domain;
    struct list_head entry;
    unsigned int owner_cnt;
    void * owner;
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
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iommu_group {
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
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iommu_group {
    struct kobject kobj;
    struct kobject * devices_kobj;
    struct list_head devices;
    struct mutex mutex;
    struct blocking_notifier_head notifier;
    void * iommu_data;
    void (*)(void *) iommu_data_release;
    char * name;
    int id;
    struct iommu_domain * default_domain;
    struct iommu_domain * domain;
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head entry</code>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct iommu_domain * blocking_domain</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int owner_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>void * owner</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blocking_notifier_head notifier</code>
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
<code>struct xarray pasid_array</code>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct kobject kobj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kobject * devices_kobj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head devices</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex mutex</code>
</li>
<li>
<b>Field removed. </b>
<code>struct blocking_notifier_head notifier</code>
</li>
<li>
<b>Field removed. </b>
<code>void * iommu_data</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(void *) iommu_data_release</code>
</li>
<li>
<b>Field removed. </b>
<code>char * name</code>
</li>
<li>
<b>Field removed. </b>
<code>int id</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_domain * default_domain</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iommu_domain * domain</code>
</li>
</ul>
</details>
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
