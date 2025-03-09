# Function: <code>bpf_trace_run5</code>

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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567760,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1137",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567760,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625312,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1182",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/char/random.c:__bpf_trace_credit_entropy_bits",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625312,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685360,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1351",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685360,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732384,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732384,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845424,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1869",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "fs/io_uring.c:__bpf_trace_io_uring_submit_sqe",
        "fs/io_uring.c:__bpf_trace_io_uring_queue_async_work",
        "fs/io_uring.c:__bpf_trace_io_uring_create",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845424,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842752,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2125",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "fs/io_uring.c:__bpf_trace_io_uring_submit_sqe",
        "fs/io_uring.c:__bpf_trace_io_uring_queue_async_work",
        "fs/io_uring.c:__bpf_trace_io_uring_create",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842752,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846400,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1821",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "fs/io_uring.c:__bpf_trace_io_uring_submit_sqe",
        "fs/io_uring.c:__bpf_trace_io_uring_queue_async_work",
        "fs/io_uring.c:__bpf_trace_io_uring_create",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "drivers/iommu/intel/trace.c:__bpf_trace_qi_submit",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg",
        "net/mptcp/protocol.c:__bpf_trace_ack_update_msk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846400,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046192,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1905",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/io_uring.c:__bpf_trace_io_uring_queue_async_work",
        "fs/io_uring.c:__bpf_trace_io_uring_create",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "drivers/iommu/intel/trace.c:__bpf_trace_qi_submit",
        "drivers/base/trace.c:__bpf_trace_devres",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg",
        "net/mptcp/protocol.c:__bpf_trace_ack_update_msk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046192,
      "name": "bpf_trace_run5",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302384,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2086",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_range",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_journal_start",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow",
        "io_uring/io_uring.c:__bpf_trace_io_uring_task_add",
        "io_uring/io_uring.c:__bpf_trace_io_uring_fail_link",
        "io_uring/io_uring.c:__bpf_trace_io_uring_register",
        "io_uring/io_uring.c:__bpf_trace_io_uring_create",
        "drivers/iommu/intel/trace.c:__bpf_trace_qi_submit",
        "drivers/base/trace.c:__bpf_trace_devres",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg",
        "net/mptcp/protocol.c:__bpf_trace_ack_update_msk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302384,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581627824,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2309",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/trace/rv/rv.c:__bpf_trace_event_da_monitor_id",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_cache_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_range",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow",
        "io_uring/io_uring.c:__bpf_trace_io_uring_register",
        "io_uring/io_uring.c:__bpf_trace_io_uring_create",
        "drivers/iommu/intel/trace.c:__bpf_trace_qi_submit",
        "drivers/base/trace.c:__bpf_trace_devres",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg",
        "net/mptcp/protocol.c:__bpf_trace_ack_update_msk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627824,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767744,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2318",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/trace/rv/rv.c:__bpf_trace_event_da_monitor_id",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_cache_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "mm/ksm.c:__bpf_trace_ksm_merge_with_ksm_page",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_range",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow",
        "io_uring/io_uring.c:__bpf_trace_io_uring_register",
        "io_uring/io_uring.c:__bpf_trace_io_uring_create",
        "drivers/iommu/intel/trace.c:__bpf_trace_qi_submit",
        "drivers/base/trace.c:__bpf_trace_devres",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/devlink/leftover.c:__bpf_trace_devlink_hwmsg",
        "net/mptcp/protocol.c:__bpf_trace_ack_update_msk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767744,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885872,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2423",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "kernel/sched/core.c:__bpf_trace_sched_compute_energy_tp",
        "kernel/trace/rv/rv.c:__bpf_trace_event_da_monitor_id",
        "kernel/bpf/core.c:__bpf_trace_xdp_devmap_xmit",
        "kernel/bpf/core.c:__bpf_trace_xdp_cpumap_kthread",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_cache_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "mm/ksm.c:__bpf_trace_ksm_merge_with_ksm_page",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_track_range",
        "fs/ext4/super.c:__bpf_trace_ext4_fc_replay",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start_class",
        "io_uring/io_uring.c:__bpf_trace_io_uring_cqe_overflow",
        "io_uring/io_uring.c:__bpf_trace_io_uring_register",
        "io_uring/io_uring.c:__bpf_trace_io_uring_create",
        "drivers/iommu/intel/trace.c:__bpf_trace_qi_submit",
        "drivers/base/trace.c:__bpf_trace_devres",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "drivers/interconnect/core.c:__bpf_trace_icc_set_bw",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/devlink/core.c:__bpf_trace_devlink_hwmsg",
        "net/mptcp/protocol.c:__bpf_trace_ack_update_msk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885872,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492048400,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/soc/qcom/rpmh-rsc.c:__bpf_trace_rpmh_send_msg",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_get_power",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492048400,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225940120,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_get_power",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225940120,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285210752,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:__bpf_trace_vfio_pci_npu2_mmap",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:__bpf_trace_vfio_pci_nvgpu_mmap",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_cpu_get_power",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285210752,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701184,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701184,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647392,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647392,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692432,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692432,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
```

```json
{
  "name": "bpf_trace_run5",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580754864,
      "name": "bpf_trace_run5",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1375",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:__bpf_trace_vector_mod",
        "kernel/cpu.c:__bpf_trace_cpuhp_multi_enter",
        "kernel/signal.c:__bpf_trace_signal_generate",
        "mm/slab_common.c:__bpf_trace_mm_page_alloc_extfrag",
        "mm/slab_common.c:__bpf_trace_kmem_alloc",
        "mm/compaction.c:__bpf_trace_mm_compaction_begin",
        "mm/khugepaged.c:__bpf_trace_mm_collapse_huge_page_isolate",
        "fs/dax.c:__bpf_trace_dax_pmd_insert_mapping_class",
        "fs/ext4/super.c:__bpf_trace_ext4_es_shrink",
        "fs/ext4/super.c:__bpf_trace_ext4_remove_blocks",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_handle_unwritten_extents",
        "fs/ext4/super.c:__bpf_trace_ext4_direct_IO_exit",
        "fs/ext4/super.c:__bpf_trace_ext4__mballoc",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_start",
        "drivers/char/random.c:__bpf_trace_xfer_secondary_pool",
        "drivers/ras/ras.c:__bpf_trace_aer_event",
        "drivers/ras/ras.c:__bpf_trace_extlog_mem_event",
        "net/core/net-traces.c:__bpf_trace_neigh_update",
        "net/core/net-traces.c:__bpf_trace_neigh_create",
        "net/core/net-traces.c:__bpf_trace_br_fdb_update",
        "net/core/net-traces.c:__bpf_trace_br_fdb_add",
        "net/core/devlink.c:__bpf_trace_devlink_hwmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580754864,
      "name": "bpf_trace_run5",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
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
void bpf_trace_run5(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4)
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
