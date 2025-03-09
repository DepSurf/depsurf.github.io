# Function: <code>mtree_load</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * mtree_load(struct maple_tree * mt, long unsigned int index)
```

```json
{
  "name": "mtree_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595797808,
      "name": "mtree_load",
      "external": true,
      "loc": "lib/maple_tree.c:6152",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:find_active_uprobe",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:do_mincore",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:vma_to_resize",
        "mm/madvise.c:madvise_populate",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595797808,
      "name": "mtree_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * mtree_load(struct maple_tree * mt, long unsigned int index)
```

```json
{
  "name": "mtree_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596323168,
      "name": "mtree_load",
      "external": true,
      "loc": "lib/maple_tree.c:6202",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:do_mincore",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:vma_to_resize",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323168,
      "name": "mtree_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 854
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * mtree_load(struct maple_tree * mt, long unsigned int index)
```

```json
{
  "name": "mtree_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597211488,
      "name": "mtree_load",
      "external": true,
      "loc": "lib/maple_tree.c:6269",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "kernel/irq/irqdesc.c:kstat_irqs_usr",
        "kernel/irq/irqdesc.c:kstat_irqs_cpu",
        "kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu",
        "kernel/irq/irqdesc.c:irq_get_percpu_devid_partition",
        "kernel/irq/irqdesc.c:irq_set_percpu_devid_partition",
        "kernel/irq/irqdesc.c:__irq_get_desc_lock",
        "kernel/irq/irqdesc.c:generic_handle_irq_safe",
        "kernel/irq/irqdesc.c:generic_handle_irq",
        "kernel/irq/irqdesc.c:free_desc",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:do_mincore",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:vma_to_resize",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597211488,
      "name": "mtree_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
    }
  ]
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void * mtree_load(struct maple_tree * mt, long unsigned int index)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
