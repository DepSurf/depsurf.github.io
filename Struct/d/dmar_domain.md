# Struct: <code>dmar_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head subdevices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    u32 default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head subdevices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    u32 default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    u8 has_iotlb_device;
    u8 iommu_coherency;
    u8 iommu_snooping;
    struct list_head devices;
    struct list_head subdevices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_superpage;
    u64 max_addr;
    u32 default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    u8 has_iotlb_device;
    u8 iommu_coherency;
    u8 force_snooping;
    u8 set_pte_snp;
    struct list_head devices;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    struct xarray iommu_array;
    u8 has_iotlb_device;
    u8 iommu_coherency;
    u8 force_snooping;
    u8 set_pte_snp;
    u8 use_first_level;
    spinlock_t lock;
    struct list_head devices;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    struct xarray iommu_array;
    u8 has_iotlb_device;
    u8 iommu_coherency;
    u8 force_snooping;
    u8 set_pte_snp;
    u8 use_first_level;
    spinlock_t lock;
    struct list_head devices;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int iommu_superpage;
    u64 max_addr;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    struct xarray iommu_array;
    u8 has_iotlb_device;
    u8 iommu_coherency;
    u8 force_snooping;
    u8 set_pte_snp;
    u8 use_first_level;
    u8 dirty_tracking;
    u8 nested_parent;
    u8 has_mappings;
    spinlock_t lock;
    struct list_head devices;
    struct list_head dev_pasids;
    int iommu_superpage;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    u64 max_addr;
    spinlock_t s1_lock;
    struct list_head s1_domains;
    struct dmar_domain * s2_domain;
    long unsigned int s1_pgtbl;
    struct iommu_hwpt_vtd_s1 s1_cfg;
    struct list_head s2_link;
    struct iommu_domain domain;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
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
<code>bool has_iotlb_device</code>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int auxd_refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head auxd</code>
</li>
<li>
<b>Field added. </b>
<code>int default_pasid</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head subdevices</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int auxd_refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head auxd</code>
</li>
<li>
<b>Field type changed. </b>
<code>int default_pasid</code> ➡️ <code>u32 default_pasid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int iommu_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool has_iotlb_device</code> ➡️ <code>u8 has_iotlb_device</code>
</li>
<li>
<b>Field type changed. </b>
<code>int iommu_coherency</code> ➡️ <code>u8 iommu_coherency</code>
</li>
<li>
<b>Field type changed. </b>
<code>int iommu_snooping</code> ➡️ <code>u8 iommu_snooping</code>
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
<code>u8 force_snooping</code>
</li>
<li>
<b>Field added. </b>
<code>u8 set_pte_snp</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 iommu_snooping</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head subdevices</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 default_pasid</code>
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
<code>struct xarray iommu_array</code>
</li>
<li>
<b>Field added. </b>
<code>u8 use_first_level</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int[128] iommu_refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>u16[128] iommu_did</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iova_domain iovad</code>
</li>
<li>
<b>Field removed. </b>
<code>int flags</code>
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
<code>u8 dirty_tracking</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nested_parent</code>
</li>
<li>
<b>Field added. </b>
<code>u8 has_mappings</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head dev_pasids</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t s1_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head s1_domains</code>
</li>
<li>
<b>Field added. </b>
<code>struct dmar_domain * s2_domain</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int s1_pgtbl</code>
</li>
<li>
<b>Field added. </b>
<code>struct iommu_hwpt_vtd_s1 s1_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head s2_link</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct dmar_domain {
    int nid;
    unsigned int[128] iommu_refcnt;
    u16[128] iommu_did;
    unsigned int auxd_refcnt;
    bool has_iotlb_device;
    struct list_head devices;
    struct list_head auxd;
    struct iova_domain iovad;
    struct dma_pte * pgd;
    int gaw;
    int agaw;
    int flags;
    int iommu_coherency;
    int iommu_snooping;
    int iommu_count;
    int iommu_superpage;
    u64 max_addr;
    int default_pasid;
    struct iommu_domain domain;
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
