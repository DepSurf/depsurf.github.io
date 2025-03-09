# Struct: <code>remap_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * mfn;
    bool contiguous;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * mfn;
    bool contiguous;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * mfn;
    bool contiguous;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * mfn;
    bool contiguous;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * mfn;
    bool contiguous;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
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
struct remap_data {
    xen_pfn_t * fgfn;
    int nr_fgfn;
    pgprot_t prot;
    domid_t domid;
    struct vm_area_struct * vma;
    int index;
    struct page * * pages;
    struct xen_remap_gfn_info * info;
    int * err_ptr;
    int mapped;
    int[1] h_errs;
    xen_ulong_t[1] h_idxs;
    xen_pfn_t[1] h_gpfns;
    int h_iter;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>xen_pfn_t * pfn</code>
</li>
<li>
<b>Field added. </b>
<code>bool no_translate</code>
</li>
<li>
<b>Field removed. </b>
<code>xen_pfn_t * mfn</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>xen_pfn_t * fgfn</code>
</li>
<li>
<b>Field added. </b>
<code>int nr_fgfn</code>
</li>
<li>
<b>Field added. </b>
<code>domid_t domid</code>
</li>
<li>
<b>Field added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Field added. </b>
<code>int index</code>
</li>
<li>
<b>Field added. </b>
<code>struct page * * pages</code>
</li>
<li>
<b>Field added. </b>
<code>struct xen_remap_gfn_info * info</code>
</li>
<li>
<b>Field added. </b>
<code>int * err_ptr</code>
</li>
<li>
<b>Field added. </b>
<code>int mapped</code>
</li>
<li>
<b>Field added. </b>
<code>int[1] h_errs</code>
</li>
<li>
<b>Field added. </b>
<code>xen_ulong_t[1] h_idxs</code>
</li>
<li>
<b>Field added. </b>
<code>xen_pfn_t[1] h_gpfns</code>
</li>
<li>
<b>Field added. </b>
<code>int h_iter</code>
</li>
<li>
<b>Field removed. </b>
<code>xen_pfn_t * pfn</code>
</li>
<li>
<b>Field removed. </b>
<code>bool contiguous</code>
</li>
<li>
<b>Field removed. </b>
<code>bool no_translate</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mmu_update * mmu_update</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
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
struct remap_data {
    xen_pfn_t * pfn;
    bool contiguous;
    bool no_translate;
    pgprot_t prot;
    struct mmu_update * mmu_update;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
