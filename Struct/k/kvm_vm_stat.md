# Struct: <code>kvm_vm_stat</code>

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
struct kvm_vm_stat {
    ulong mmu_shadow_zapped;
    ulong mmu_pte_write;
    ulong mmu_pte_updated;
    ulong mmu_pde_zapped;
    ulong mmu_flooded;
    ulong mmu_recycled;
    ulong mmu_cache_miss;
    ulong mmu_unsync;
    ulong remote_tlb_flush;
    ulong lpages;
    ulong nx_lpage_splits;
    ulong max_mmu_page_hash_collisions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_vm_stat {
    ulong mmu_shadow_zapped;
    ulong mmu_pte_write;
    ulong mmu_pde_zapped;
    ulong mmu_flooded;
    ulong mmu_recycled;
    ulong mmu_cache_miss;
    ulong mmu_unsync;
    ulong remote_tlb_flush;
    ulong lpages;
    ulong nx_lpage_splits;
    ulong max_mmu_page_hash_collisions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_vm_stat {
    struct kvm_vm_stat_generic generic;
    u64 mmu_shadow_zapped;
    u64 mmu_pte_write;
    u64 mmu_pde_zapped;
    u64 mmu_flooded;
    u64 mmu_recycled;
    u64 mmu_cache_miss;
    u64 mmu_unsync;
    atomic64_t pages_4k;
    atomic64_t pages_2m;
    atomic64_t pages_1g;
    atomic64_t[3] pages;
    u64 nx_lpage_splits;
    u64 max_mmu_page_hash_collisions;
    u64 max_mmu_rmap_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_vm_stat {
    struct kvm_vm_stat_generic generic;
    u64 mmu_shadow_zapped;
    u64 mmu_pte_write;
    u64 mmu_pde_zapped;
    u64 mmu_flooded;
    u64 mmu_recycled;
    u64 mmu_cache_miss;
    u64 mmu_unsync;
    atomic64_t pages_4k;
    atomic64_t pages_2m;
    atomic64_t pages_1g;
    atomic64_t[3] pages;
    u64 nx_lpage_splits;
    u64 max_mmu_page_hash_collisions;
    u64 max_mmu_rmap_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_vm_stat {
    struct kvm_vm_stat_generic generic;
    u64 mmu_shadow_zapped;
    u64 mmu_pte_write;
    u64 mmu_pde_zapped;
    u64 mmu_flooded;
    u64 mmu_recycled;
    u64 mmu_cache_miss;
    u64 mmu_unsync;
    atomic64_t pages_4k;
    atomic64_t pages_2m;
    atomic64_t pages_1g;
    atomic64_t[3] pages;
    u64 nx_lpage_splits;
    u64 max_mmu_page_hash_collisions;
    u64 max_mmu_rmap_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_vm_stat {
    struct kvm_vm_stat_generic generic;
    u64 mmu_shadow_zapped;
    u64 mmu_pte_write;
    u64 mmu_pde_zapped;
    u64 mmu_flooded;
    u64 mmu_recycled;
    u64 mmu_cache_miss;
    u64 mmu_unsync;
    atomic64_t pages_4k;
    atomic64_t pages_2m;
    atomic64_t pages_1g;
    atomic64_t[3] pages;
    u64 nx_lpage_splits;
    u64 max_mmu_page_hash_collisions;
    u64 max_mmu_rmap_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_vm_stat {
    struct kvm_vm_stat_generic generic;
    u64 mmu_shadow_zapped;
    u64 mmu_pte_write;
    u64 mmu_pde_zapped;
    u64 mmu_flooded;
    u64 mmu_recycled;
    u64 mmu_cache_miss;
    u64 mmu_unsync;
    atomic64_t pages_4k;
    atomic64_t pages_2m;
    atomic64_t pages_1g;
    atomic64_t[3] pages;
    u64 nx_lpage_splits;
    u64 max_mmu_page_hash_collisions;
    u64 max_mmu_rmap_size;
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
struct kvm_vm_stat {
    ulong remote_tlb_flush;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kvm_vm_stat {
    ulong remote_tlb_flush;
    ulong num_2M_pages;
    ulong num_1G_pages;
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
struct kvm_vm_stat {
    ulong mmu_shadow_zapped;
    ulong mmu_pte_write;
    ulong mmu_pte_updated;
    ulong mmu_pde_zapped;
    ulong mmu_flooded;
    ulong mmu_recycled;
    ulong mmu_cache_miss;
    ulong mmu_unsync;
    ulong remote_tlb_flush;
    ulong lpages;
    ulong nx_lpage_splits;
    ulong max_mmu_page_hash_collisions;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>ulong mmu_pte_updated</code>
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
<code>struct kvm_vm_stat_generic generic</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t pages_4k</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t pages_2m</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t pages_1g</code>
</li>
<li>
<b>Field added. </b>
<code>atomic64_t[3] pages</code>
</li>
<li>
<b>Field added. </b>
<code>u64 max_mmu_rmap_size</code>
</li>
<li>
<b>Field removed. </b>
<code>ulong remote_tlb_flush</code>
</li>
<li>
<b>Field removed. </b>
<code>ulong lpages</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_shadow_zapped</code> ➡️ <code>u64 mmu_shadow_zapped</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_pte_write</code> ➡️ <code>u64 mmu_pte_write</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_pde_zapped</code> ➡️ <code>u64 mmu_pde_zapped</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_flooded</code> ➡️ <code>u64 mmu_flooded</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_recycled</code> ➡️ <code>u64 mmu_recycled</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_cache_miss</code> ➡️ <code>u64 mmu_cache_miss</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong mmu_unsync</code> ➡️ <code>u64 mmu_unsync</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong nx_lpage_splits</code> ➡️ <code>u64 nx_lpage_splits</code>
</li>
<li>
<b>Field type changed. </b>
<code>ulong max_mmu_page_hash_collisions</code> ➡️ <code>u64 max_mmu_page_hash_collisions</code>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_vm_stat {
    ulong remote_tlb_flush;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_vm_stat {
    ulong remote_tlb_flush;
    ulong num_2M_pages;
    ulong num_1G_pages;
}
```
</details>
</li>
</ul>
