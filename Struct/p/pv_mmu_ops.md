# Struct: <code>pv_mmu_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_single;
    void (*)(const struct cpumask *, struct mm_struct *, long unsigned int, long unsigned int) flush_tlb_others;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    void (*)(struct mm_struct *, long unsigned int, pmd_t *, pmd_t) set_pmd_at;
    void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update;
    void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update_defer;
    void (*)(struct mm_struct *, long unsigned int, pmd_t *) pmd_update;
    void (*)(struct mm_struct *, long unsigned int, pmd_t *) pmd_update_defer;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_single;
    void (*)(const struct cpumask *, struct mm_struct *, long unsigned int, long unsigned int) flush_tlb_others;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    void (*)(struct mm_struct *, long unsigned int, pmd_t *, pmd_t) set_pmd_at;
    void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_single;
    void (*)(const struct cpumask *, struct mm_struct *, long unsigned int, long unsigned int) flush_tlb_others;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    void (*)(struct mm_struct *, long unsigned int, pmd_t *, pmd_t) set_pmd_at;
    void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_single;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    void (*)(struct mm_struct *, long unsigned int, pmd_t *, pmd_t) set_pmd_at;
    void (*)(struct mm_struct *, long unsigned int, pud_t *, pud_t) set_pud_at;
    void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    long unsigned int (*)() read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)(long unsigned int, int, bool) notify_page_enc_status_changed;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)(long unsigned int, int, bool) notify_page_enc_status_changed;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)(long unsigned int, int, bool) notify_page_enc_status_changed;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *) enter_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    void (*)(long unsigned int, int, bool) notify_page_enc_status_changed;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *) enter_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct paravirt_callee_save p4d_val;
    struct paravirt_callee_save make_p4d;
    void (*)(pgd_t *, pgd_t) set_pgd;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
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
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
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
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update_defer</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pmd_t *) pmd_update</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pmd_t *) pmd_update_defer</code>
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
<code>void (*)(struct mm_struct *, long unsigned int) alloc_p4d</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(long unsigned int) release_p4d</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pud_t *, pud_t) set_pud_at</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(p4d_t *, p4d_t) set_p4d</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(pgd_t *, pgd_t) set_pgd</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(const struct cpumask *, struct mm_struct *, long unsigned int, long unsigned int) flush_tlb_others</code> ➡️ <code>void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others</code>
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
<code>void (*)(long unsigned int) flush_tlb_one_user</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) flush_tlb_single</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pmd_t *, pmd_t) set_pmd_at</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pud_t *, pud_t) set_pud_at</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pte_t *) pte_update</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct mmu_gather *, void *) tlb_remove_table</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int (*)() read_cr2</code> ➡️ <code>struct paravirt_callee_save read_cr2</code>
</li>
<li>
<b>Field type changed. </b>
<code>pte_t (*)(struct mm_struct *, long unsigned int, pte_t *) ptep_modify_prot_start</code> ➡️ <code>pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit</code> ➡️ <code>void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit</code>
</li>
</ul>
</details>
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
<code>struct paravirt_callee_save p4d_val</code>
</li>
<li>
<b>Field added. </b>
<code>struct paravirt_callee_save make_p4d</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(pgd_t *, pgd_t) set_pgd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_multi</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others</code>
</li>
</ul>
</details>
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
<code>void (*)(long unsigned int, int, bool) notify_page_enc_status_changed</code>
</li>
</ul>
</details>
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
<code>void (*)(struct mm_struct *) enter_mmap</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, struct mm_struct *) activate_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, struct mm_struct *) dup_mmap</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pv_mmu_ops {
    void (*)() flush_tlb_user;
    void (*)() flush_tlb_kernel;
    void (*)(long unsigned int) flush_tlb_one_user;
    void (*)(const struct cpumask *, const struct flush_tlb_info *) flush_tlb_others;
    void (*)(struct mmu_gather *, void *) tlb_remove_table;
    void (*)(struct mm_struct *) exit_mmap;
    struct paravirt_callee_save read_cr2;
    void (*)(long unsigned int) write_cr2;
    long unsigned int (*)() read_cr3;
    void (*)(long unsigned int) write_cr3;
    void (*)(struct mm_struct *, struct mm_struct *) activate_mm;
    void (*)(struct mm_struct *, struct mm_struct *) dup_mmap;
    int (*)(struct mm_struct *) pgd_alloc;
    void (*)(struct mm_struct *, pgd_t *) pgd_free;
    void (*)(struct mm_struct *, long unsigned int) alloc_pte;
    void (*)(struct mm_struct *, long unsigned int) alloc_pmd;
    void (*)(struct mm_struct *, long unsigned int) alloc_pud;
    void (*)(struct mm_struct *, long unsigned int) alloc_p4d;
    void (*)(long unsigned int) release_pte;
    void (*)(long unsigned int) release_pmd;
    void (*)(long unsigned int) release_pud;
    void (*)(long unsigned int) release_p4d;
    void (*)(pte_t *, pte_t) set_pte;
    void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at;
    void (*)(pmd_t *, pmd_t) set_pmd;
    pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start;
    void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit;
    struct paravirt_callee_save pte_val;
    struct paravirt_callee_save make_pte;
    struct paravirt_callee_save pgd_val;
    struct paravirt_callee_save make_pgd;
    void (*)(pud_t *, pud_t) set_pud;
    struct paravirt_callee_save pmd_val;
    struct paravirt_callee_save make_pmd;
    struct paravirt_callee_save pud_val;
    struct paravirt_callee_save make_pud;
    void (*)(p4d_t *, p4d_t) set_p4d;
    struct pv_lazy_ops lazy_mode;
    void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap;
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save read_cr2</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) write_cr2</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int (*)() read_cr3</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) write_cr3</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, struct mm_struct *) activate_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, struct mm_struct *) dup_mmap</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct mm_struct *) pgd_alloc</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, pgd_t *) pgd_free</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int) alloc_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int) alloc_pmd</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int) alloc_pud</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int) alloc_p4d</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) release_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) release_pmd</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) release_pud</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(long unsigned int) release_p4d</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(pte_t *, pte_t) set_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct mm_struct *, long unsigned int, pte_t *, pte_t) set_pte_at</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(pmd_t *, pmd_t) set_pmd</code>
</li>
<li>
<b>Field removed. </b>
<code>pte_t (*)(struct vm_area_struct *, long unsigned int, pte_t *) ptep_modify_prot_start</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct vm_area_struct *, long unsigned int, pte_t *, pte_t) ptep_modify_prot_commit</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save pte_val</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save make_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save pgd_val</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save make_pgd</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(pud_t *, pud_t) set_pud</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save pmd_val</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save make_pmd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save pud_val</code>
</li>
<li>
<b>Field removed. </b>
<code>struct paravirt_callee_save make_pud</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(p4d_t *, p4d_t) set_p4d</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pv_lazy_ops lazy_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(unsigned int, phys_addr_t, pgprot_t) set_fixmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
