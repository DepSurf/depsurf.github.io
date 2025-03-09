# Function: <code>bpf_trace_run4</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567680,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1136",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567680,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625232,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1181",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_direct_reclaim_begin_template",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625232,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685200,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1350",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pte_at",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685200,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732224,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pte_at",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732224,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845264,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1868",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/iommu/intel/trace.c:__bpf_trace_dma_map_sg",
        "drivers/iommu/intel/trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845264,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842576,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2124",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/iommu/intel/trace.c:__bpf_trace_dma_map_sg",
        "drivers/iommu/intel/trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842576,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846240,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1820",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/io_uring.c:__bpf_trace_io_uring_complete",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846240,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046032,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1904",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/io_uring.c:__bpf_trace_io_uring_task_run",
        "fs/io_uring.c:__bpf_trace_io_uring_complete",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_scan_exit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046032,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302208,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2085",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_throttled",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/huge_memory.c:__bpf_trace_hugepage_update",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_dentry",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_commit_stop",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_scan_exit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "io_uring/io_uring.c:__bpf_trace_io_uring_req_failed",
        "io_uring/io_uring.c:__bpf_trace_io_uring_defer",
        "io_uring/io_uring.c:__bpf_trace_io_uring_file_get",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302208,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581627584,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2308",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_throttled",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/huge_memory.c:__bpf_trace_hugepage_update",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_dentry",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_commit_stop",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_scan_exit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "io_uring/io_uring.c:__bpf_trace_io_uring_short_write",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bulk",
        "drivers/scsi/sd_zbc.c:__bpf_trace_scsi_zone_wp_update",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup",
        "lib/maple_tree.c:__bpf_trace_ma_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627584,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767504,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2317",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/smp.c:__bpf_trace_csd_queue_cpu",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/trace/trace_osnoise.c:__bpf_trace_irq_noise",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_throttled",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/ksm.c:__bpf_trace_ksm_merge_one_page",
        "mm/huge_memory.c:__bpf_trace_hugepage_update",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_dio_rw_begin",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_dentry",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_commit_stop",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_scan_exit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "io_uring/io_uring.c:__bpf_trace_io_uring_short_write",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bulk",
        "drivers/scsi/sd_zbc.c:__bpf_trace_scsi_zone_wp_update",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup",
        "net/devlink/leftover.c:__bpf_trace_devlink_health_recover_aborted",
        "lib/maple_tree.c:__bpf_trace_ma_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767504,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885632,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2422",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_multi",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_numa_pair_template",
        "kernel/sched/core.c:__bpf_trace_sched_switch",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/smp.c:__bpf_trace_csd_queue_cpu",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/trace/trace_osnoise.c:__bpf_trace_irq_noise",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_throttled",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/mmap_lock.c:__bpf_trace_mmap_lock_acquire_returned",
        "mm/ksm.c:__bpf_trace_ksm_merge_one_page",
        "mm/huge_memory.c:__bpf_trace_hugepage_update",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "fs/fs-writeback.c:__bpf_trace_writeback_queue_io",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/iomap/trace.c:__bpf_trace_iomap_dio_rw_begin",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_dentry",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_commit_stop",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_scan_exit",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "security/selinux/avc.c:__bpf_trace_selinux_audited",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "io_uring/io_uring.c:__bpf_trace_io_uring_short_write",
        "drivers/base/regmap/regmap.c:__bpf_trace_regmap_bulk",
        "drivers/scsi/sd_zbc.c:__bpf_trace_scsi_zone_wp_update",
        "drivers/gpu/drm/drm_trace_points.c:__bpf_trace_drm_vblank_event",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_actor",
        "net/core/net-traces.c:__bpf_trace_page_pool_release",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup",
        "net/devlink/core.c:__bpf_trace_devlink_health_recover_aborted",
        "lib/maple_tree.c:__bpf_trace_ma_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885632,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492048216,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_halt_poll_ns",
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_age_page",
        "virt/kvm/kvm_main.c:__bpf_trace_kvm_mmio",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_irq_line",
        "virt/kvm/arm/arm.c:__bpf_trace_kvm_guest_fault",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_trap_reg",
        "arch/arm64/kvm/handle_exit.c:__bpf_trace_kvm_arm_set_regset",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/soc/qcom/rpmh-rsc.c:__bpf_trace_rpmh_tx_done",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492048216,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225939836,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_regl",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_regw",
        "drivers/usb/musb/musb_trace.c:__bpf_trace_musb_regb",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225939836,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285210512,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/hash_pgtable.c:__bpf_trace_hugepage_update",
        "arch/powerpc/platforms/powernv/vas-window.c:__bpf_trace_vas_tx_win_open",
        "arch/powerpc/platforms/powernv/vas-window.c:__bpf_trace_vas_rx_win_open",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:__bpf_trace_vfio_pci_nvgpu_mmap_fault",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285210512,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701024,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pte_at",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701024,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647232,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647232,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692272,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pte_at",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692272,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```

```json
{
  "name": "bpf_trace_run4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754672,
      "name": "bpf_trace_run4",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1374",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/trace.c:__bpf_trace_xen_cpu_write_gdt_entry",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_flush_tlb_others",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_alloc_ptpage",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:__bpf_trace_xen_mmu_set_pte_at",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_free_moved",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_activate",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_alloc",
        "arch/x86/kernel/irq.c:__bpf_trace_vector_config",
        "kernel/cpu.c:__bpf_trace_cpuhp_exit",
        "kernel/cpu.c:__bpf_trace_cpuhp_enter",
        "kernel/sched/core.c:__bpf_trace_sched_swap_numa",
        "kernel/irq/matrix.c:__bpf_trace_irq_matrix_cpu",
        "kernel/dma/swiotlb.c:__bpf_trace_swiotlb_bounced",
        "kernel/cgroup/cgroup.c:__bpf_trace_cgroup_migrate",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_enqueue",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "kernel/bpf/core.c:__bpf_trace_xdp_bulk_tx",
        "kernel/rseq.c:__bpf_trace_rseq_ip_fixup",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_wakeup_kswapd",
        "mm/percpu.c:__bpf_trace_percpu_alloc_percpu_fail",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_isolate_template",
        "mm/migrate.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_swapin",
        "mm/cma.c:__bpf_trace_cma_alloc",
        "fs/dax.c:__bpf_trace_dax_pmd_load_hole_class",
        "fs/dax.c:__bpf_trace_dax_pmd_fault_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_rm_leaf",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_show_extent",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_put_in_cache",
        "fs/ext4/super.c:__bpf_trace_ext4__trim",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__map_blocks_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_convert_to_initialized_fastpath",
        "fs/ext4/super.c:__bpf_trace_ext4_fallocate_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__fallocate_mode",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_enter",
        "fs/ext4/super.c:__bpf_trace_ext4_free_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_writepages_result",
        "fs/ext4/super.c:__bpf_trace_ext4__write_end",
        "fs/ext4/super.c:__bpf_trace_ext4__write_begin",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_update_log_tail",
        "block/blk-core.c:__bpf_trace_block_rq_remap",
        "block/blk-core.c:__bpf_trace_block_bio_remap",
        "block/blk-wbt.c:__bpf_trace_wbt_timer",
        "drivers/char/random.c:__bpf_trace_random_read",
        "drivers/char/random.c:__bpf_trace_random__extract_entropy",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/iommu/intel-trace.c:__bpf_trace_dma_map",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_limit",
        "net/core/net-traces.c:__bpf_trace_page_pool_inflight",
        "net/core/net-traces.c:__bpf_trace_br_fdb_external_learn_add",
        "net/core/net-traces.c:__bpf_trace_qdisc_dequeue",
        "net/core/net-traces.c:__bpf_trace_fib_table_lookup",
        "net/core/net-traces.c:__bpf_trace_sock_exceed_buf_limit",
        "net/core/net-traces.c:__bpf_trace_net_dev_xmit",
        "net/core/devlink.c:__bpf_trace_devlink_health_recover_aborted",
        "net/ipv6/route.c:__bpf_trace_fib6_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754672,
      "name": "bpf_trace_run4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
```
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void bpf_trace_run4(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3)
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
