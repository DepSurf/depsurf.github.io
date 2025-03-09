# Struct: <code>vm_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    unsigned int flags;
    long unsigned int pgoff;
    void * virtual_address;
    struct page * cow_page;
    struct page * page;
    long unsigned int max_pgoff;
    pte_t * pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    void * virtual_address;
    struct page * cow_page;
    struct page * page;
    void * entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    const struct (anon) (anon);
    enum fault_flag flags;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    const struct (anon) (anon);
    enum fault_flag flags;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    pmd_t orig_pmd;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    const struct (anon) (anon);
    enum fault_flag flags;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    pmd_t orig_pmd;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    const struct (anon) (anon);
    enum fault_flag flags;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    pmd_t orig_pmd;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    const struct (anon) (anon);
    enum fault_flag flags;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    pmd_t orig_pmd;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vm_fault {
    const struct (anon) (anon);
    enum fault_flag flags;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    pmd_t orig_pmd;
    struct page * cow_page;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
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
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
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
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vm_fault {
    struct vm_area_struct * vma;
    unsigned int flags;
    gfp_t gfp_mask;
    long unsigned int pgoff;
    long unsigned int address;
    pmd_t * pmd;
    pud_t * pud;
    pte_t orig_pte;
    struct page * cow_page;
    struct mem_cgroup * memcg;
    struct page * page;
    pte_t * pte;
    spinlock_t * ptl;
    pgtable_t prealloc_pte;
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
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Field added. </b>
<code>void * entry</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int max_pgoff</code>
</li>
<li>
<b>Field removed. </b>
<code>pte_t * pte</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Field added. </b>
<code>pmd_t * pmd</code>
</li>
<li>
<b>Field added. </b>
<code>pte_t orig_pte</code>
</li>
<li>
<b>Field added. </b>
<code>struct mem_cgroup * memcg</code>
</li>
<li>
<b>Field added. </b>
<code>pte_t * pte</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t * ptl</code>
</li>
<li>
<b>Field added. </b>
<code>pgtable_t prealloc_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>void * virtual_address</code>
</li>
<li>
<b>Field removed. </b>
<code>void * entry</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>pud_t * pud</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>struct mem_cgroup * memcg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct (anon) (anon)</code>
</li>
<li>
<b>Field removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Field removed. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int pgoff</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int flags</code> ➡️ <code>enum fault_flag flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>pmd_t orig_pmd</code>
</li>
</ul>
</details>
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
