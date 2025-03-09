# Struct: <code>mm_walk_ops</code>

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
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
    enum page_walk_lock walk_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry;
    int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry;
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma;
    void (*)(struct mm_walk *) post_vma;
    enum page_walk_lock walk_lock;
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
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
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
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
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
struct mm_walk_ops {
    int (*)(pud_t *, long unsigned int, long unsigned int, struct mm_walk *) pud_entry;
    int (*)(pmd_t *, long unsigned int, long unsigned int, struct mm_walk *) pmd_entry;
    int (*)(pte_t *, long unsigned int, long unsigned int, struct mm_walk *) pte_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole;
    int (*)(pte_t *, long unsigned int, long unsigned int, long unsigned int, struct mm_walk *) hugetlb_entry;
    int (*)(long unsigned int, long unsigned int, struct mm_walk *) test_walk;
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
<code>int (*)(pgd_t *, long unsigned int, long unsigned int, struct mm_walk *) pgd_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(p4d_t *, long unsigned int, long unsigned int, struct mm_walk *) p4d_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(long unsigned int, long unsigned int, struct mm_walk *) pre_vma</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mm_walk *) post_vma</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(long unsigned int, long unsigned int, struct mm_walk *) pte_hole</code> ➡️ <code>int (*)(long unsigned int, long unsigned int, int, struct mm_walk *) pte_hole</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum page_walk_lock walk_lock</code>
</li>
</ul>
</details>
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
