# Struct: <code>kvm_mmu</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, gpa_t, u32, bool) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) gva_to_gpa;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) translate_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page;
    void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg;
    void (*)(struct kvm_vcpu *, struct kvm_mmu_page *, u64 *, const void *) update_pte;
    hpa_t root_hpa;
    gpa_t root_pgd;
    union kvm_mmu_role mmu_role;
    u8 root_level;
    u8 shadow_root_level;
    u8 ept_ad;
    bool direct_map;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u32 pkru_mask;
    u64 * pae_root;
    u64 * lm_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u8 last_nonleaf_level;
    bool nx;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, gpa_t, u32, bool) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) gva_to_gpa;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) translate_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page;
    void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg;
    hpa_t root_hpa;
    gpa_t root_pgd;
    union kvm_mmu_role mmu_role;
    u8 root_level;
    u8 shadow_root_level;
    u8 ept_ad;
    bool direct_map;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u32 pkru_mask;
    u64 * pae_root;
    u64 * pml4_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u8 last_nonleaf_level;
    bool nx;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, gpa_t, u32, bool) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) gva_to_gpa;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) translate_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page;
    void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg;
    hpa_t root_hpa;
    gpa_t root_pgd;
    union kvm_mmu_role mmu_role;
    u8 root_level;
    u8 shadow_root_level;
    u8 ept_ad;
    bool direct_map;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u32 pkru_mask;
    u64 * pae_root;
    u64 * pml4_root;
    u64 * pml5_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, struct kvm_page_fault *) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, struct kvm_mmu *, gpa_t, u64, struct x86_exception *) gva_to_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page;
    void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg;
    struct kvm_mmu_root_info root;
    union kvm_cpu_role cpu_role;
    union kvm_mmu_page_role root_role;
    u32 pkru_mask;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u64 * pae_root;
    u64 * pml4_root;
    u64 * pml5_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, struct kvm_page_fault *) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, struct kvm_mmu *, gpa_t, u64, struct x86_exception *) gva_to_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page;
    void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg;
    struct kvm_mmu_root_info root;
    union kvm_cpu_role cpu_role;
    union kvm_mmu_page_role root_role;
    u32 pkru_mask;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u64 * pae_root;
    u64 * pml4_root;
    u64 * pml5_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, struct kvm_page_fault *) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, struct kvm_mmu *, gpa_t, u64, struct x86_exception *) gva_to_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *, int) sync_spte;
    struct kvm_mmu_root_info root;
    union kvm_cpu_role cpu_role;
    union kvm_mmu_page_role root_role;
    u32 pkru_mask;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u64 * pae_root;
    u64 * pml4_root;
    u64 * pml5_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, struct kvm_page_fault *) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, struct kvm_mmu *, gpa_t, u64, struct x86_exception *) gva_to_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *, int) sync_spte;
    struct kvm_mmu_root_info root;
    union kvm_cpu_role cpu_role;
    union kvm_mmu_page_role root_role;
    u32 pkru_mask;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u64 * pae_root;
    u64 * pml4_root;
    u64 * pml5_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u64[4] pdptrs;
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct kvm_mmu {
    long unsigned int (*)(struct kvm_vcpu *) get_guest_pgd;
    u64 (*)(struct kvm_vcpu *, int) get_pdptr;
    int (*)(struct kvm_vcpu *, gpa_t, u32, bool) page_fault;
    void (*)(struct kvm_vcpu *, struct x86_exception *) inject_page_fault;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) gva_to_gpa;
    gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) translate_gpa;
    int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page;
    void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg;
    void (*)(struct kvm_vcpu *, struct kvm_mmu_page *, u64 *, const void *) update_pte;
    hpa_t root_hpa;
    gpa_t root_pgd;
    union kvm_mmu_role mmu_role;
    u8 root_level;
    u8 shadow_root_level;
    u8 ept_ad;
    bool direct_map;
    struct kvm_mmu_root_info[3] prev_roots;
    u8[16] permissions;
    u32 pkru_mask;
    u64 * pae_root;
    u64 * lm_root;
    struct rsvd_bits_validate shadow_zero_check;
    struct rsvd_bits_validate guest_rsvd_check;
    u8 last_nonleaf_level;
    bool nx;
    u64[4] pdptrs;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 * pml4_root</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *, struct kvm_mmu_page *, u64 *, const void *) update_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 * lm_root</code>
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
<code>u64 * pml5_root</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 last_nonleaf_level</code>
</li>
<li>
<b>Field removed. </b>
<code>bool nx</code>
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
<code>struct kvm_mmu_root_info root</code>
</li>
<li>
<b>Field added. </b>
<code>union kvm_cpu_role cpu_role</code>
</li>
<li>
<b>Field added. </b>
<code>union kvm_mmu_page_role root_role</code>
</li>
<li>
<b>Field removed. </b>
<code>gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) translate_gpa</code>
</li>
<li>
<b>Field removed. </b>
<code>hpa_t root_hpa</code>
</li>
<li>
<b>Field removed. </b>
<code>gpa_t root_pgd</code>
</li>
<li>
<b>Field removed. </b>
<code>union kvm_mmu_role mmu_role</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 root_level</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 shadow_root_level</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 ept_ad</code>
</li>
<li>
<b>Field removed. </b>
<code>bool direct_map</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct kvm_vcpu *, gpa_t, u32, bool) page_fault</code> ➡️ <code>int (*)(struct kvm_vcpu *, struct kvm_page_fault *) page_fault</code>
</li>
<li>
<b>Field type changed. </b>
<code>gpa_t (*)(struct kvm_vcpu *, gpa_t, u32, struct x86_exception *) gva_to_gpa</code> ➡️ <code>gpa_t (*)(struct kvm_vcpu *, struct kvm_mmu *, gpa_t, u64, struct x86_exception *) gva_to_gpa</code>
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
<code>int (*)(struct kvm_vcpu *, struct kvm_mmu_page *, int) sync_spte</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm_vcpu *, struct kvm_mmu_page *) sync_page</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *, gva_t, hpa_t) invlpg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
