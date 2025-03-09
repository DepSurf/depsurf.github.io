# Struct: <code>mmu_notifier_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) invalidate_page;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) invalidate_page;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) invalidate_page;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    int flags;
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) arch_invalidate_secondary_tlbs;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
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
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
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
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mmu_notifier_ops {
    void (*)(struct mmu_notifier *, struct mm_struct *) release;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_flush_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) clear_young;
    int (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) test_young;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, pte_t) change_pte;
    int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start;
    void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end;
    void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range;
    struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier;
    void (*)(struct mmu_notifier *) free_notifier;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int) invalidate_page</code>
</li>
</ul>
</details>
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
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_start</code> ➡️ <code>int (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_start</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range_end</code> ➡️ <code>void (*)(struct mmu_notifier *, const struct mmu_notifier_range *) invalidate_range_end</code>
</li>
</ul>
</details>
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
<code>struct mmu_notifier * (*)(struct mm_struct *) alloc_notifier</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mmu_notifier *) free_notifier</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) arch_invalidate_secondary_tlbs</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mmu_notifier *, struct mm_struct *, long unsigned int, long unsigned int) invalidate_range</code>
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
