# Struct: <code>iommu_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    struct iommu_dma_cookie * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_domain_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    struct iommu_dma_cookie * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_domain_ops * ops;
    long unsigned int pgsize_bitmap;
    struct iommu_domain_geometry geometry;
    struct iommu_dma_cookie * iova_cookie;
    enum iommu_page_response_code (*)(struct iommu_fault *, void *) iopf_handler;
    void * fault_data;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct mm_struct * mm;
    int users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_domain_ops * ops;
    long unsigned int pgsize_bitmap;
    struct iommu_domain_geometry geometry;
    struct iommu_dma_cookie * iova_cookie;
    enum iommu_page_response_code (*)(struct iommu_fault *, void *) iopf_handler;
    void * fault_data;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct mm_struct * mm;
    int users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_domain_ops * ops;
    const struct iommu_dirty_ops * dirty_ops;
    const struct iommu_ops * owner;
    long unsigned int pgsize_bitmap;
    struct iommu_domain_geometry geometry;
    struct iommu_dma_cookie * iova_cookie;
    enum iommu_page_response_code (*)(struct iommu_fault *, void *) iopf_handler;
    void * fault_data;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct mm_struct * mm;
    int users;
    struct list_head next;
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
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
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
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
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
<code>long unsigned int pgsize_bitmap</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<code>void * iova_cookie</code> ➡️ <code>struct iommu_dma_cookie * iova_cookie</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>const struct iommu_ops * ops</code> ➡️ <code>const struct iommu_domain_ops * ops</code>
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
<code>enum iommu_page_response_code (*)(struct iommu_fault *, void *) iopf_handler</code>
</li>
<li>
<b>Field added. </b>
<code>void * fault_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Field added. </b>
<code>int users</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct iommu_dirty_ops * dirty_ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct iommu_ops * owner</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head next</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_domain {
    unsigned int type;
    const struct iommu_ops * ops;
    long unsigned int pgsize_bitmap;
    iommu_fault_handler_t handler;
    void * handler_token;
    struct iommu_domain_geometry geometry;
    void * iova_cookie;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
