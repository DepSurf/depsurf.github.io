# Struct: <code>io_pgtable_ops</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
    int (*)(struct io_pgtable_ops *, long unsigned int, size_t, long unsigned int, struct iommu_dirty_bitmap *) read_and_clear_dirty;
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
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, size_t, int, gfp_t, size_t *) map_pages</code>
</li>
<li>
<b>Field added. </b>
<code>size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, size_t, struct iommu_iotlb_gather *) unmap_pages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int, gfp_t) map</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap</code>
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
<code>int (*)(struct io_pgtable_ops *, long unsigned int, size_t, long unsigned int, struct iommu_dirty_bitmap *) read_and_clear_dirty</code>
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
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct io_pgtable_ops {
    int (*)(struct io_pgtable_ops *, long unsigned int, phys_addr_t, size_t, int) map;
    size_t (*)(struct io_pgtable_ops *, long unsigned int, size_t, struct iommu_iotlb_gather *) unmap;
    phys_addr_t (*)(struct io_pgtable_ops *, long unsigned int) iova_to_phys;
}
```
</details>
</li>
</ul>
