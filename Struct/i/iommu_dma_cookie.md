# Struct: <code>iommu_dma_cookie</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    struct iova_fq * fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
    struct mutex mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    struct iova_fq * single_fq;
    struct iova_fq * percpu_fq;
    atomic64_t fq_flush_start_cnt;
    atomic64_t fq_flush_finish_cnt;
    struct timer_list fq_timer;
    atomic_t fq_timer_on;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
    struct iommu_dma_options options;
    struct mutex mutex;
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
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
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
<code>struct iova_fq * fq</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t fq_flush_start_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t fq_flush_finish_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list fq_timer</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t fq_timer_on</code>
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
<code>struct mutex mutex</code>
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
<code>struct iova_fq * single_fq</code>
</li>
<li>
<b>Field added. </b>
<code>struct iova_fq * percpu_fq</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_dma_options options</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iova_fq * fq</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct iommu_dma_cookie {
    enum iommu_dma_cookie_type type;
    struct iova_domain iovad;
    dma_addr_t msi_iova;
    struct list_head msi_page_list;
    struct iommu_domain * fq_domain;
}
```
</details>
</li>
</ul>
