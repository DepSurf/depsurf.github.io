# Function: <code>__find_linux_pte</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
pte_t * __find_linux_pte(pgd_t * pgdir, long unsigned int ea, bool * is_thp, unsigned int * hpage_shift)
```

```json
{
  "name": "__find_linux_pte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282718976,
      "name": "__find_linux_pte",
      "external": true,
      "loc": "arch/powerpc/mm/pgtable.c:312",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/mce_power.c:addr_to_pfn",
        "arch/powerpc/kernel/mce_power.c:addr_to_pfn",
        "arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm",
        "arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range",
        "arch/powerpc/mm/hugetlbpage.c:huge_pte_offset",
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr",
        "arch/powerpc/perf/callchain.c:read_user_stack_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282718976,
      "name": "__find_linux_pte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
    }
  ]
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
pte_t * __find_linux_pte(pgd_t * pgdir, long unsigned int ea, bool * is_thp, unsigned int * hpage_shift)
```
</details>
</li>
</ul>
