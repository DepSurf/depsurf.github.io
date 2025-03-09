# Function: <code>bpf_trace_run6</code>

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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567856,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1138",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567856,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625408,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1183",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625408,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685536,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1352",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685536,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732560,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732560,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845600,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1870",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/io_uring.c:__bpf_trace_io_uring_register",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845600,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842928,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2126",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/io_uring.c:__bpf_trace_io_uring_register",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842928,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846560,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1822",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/io_uring.c:__bpf_trace_io_uring_register",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846560,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046352,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1906",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "fs/io_uring.c:__bpf_trace_io_uring_register",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046352,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302576,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2087",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "io_uring/io_uring.c:__bpf_trace_io_uring_poll_arm",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302576,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628064,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2310",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmalloc",
        "mm/vmalloc.c:__bpf_trace_alloc_vmap_area",
        "mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_file",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628064,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767984,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2319",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmalloc",
        "mm/vmalloc.c:__bpf_trace_alloc_vmap_area",
        "mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_file",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767984,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886112,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2424",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmalloc",
        "mm/vmalloc.c:__bpf_trace_alloc_vmap_area",
        "mm/khugepaged.c:__bpf_trace_mm_khugepaged_scan_file",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_shrink_checkpoint_list",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_ioc_vrate_adj",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_state",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886112,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492048592,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492048592,
      "name": "bpf_trace_run6",
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225940412,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225940412,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285211008,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285211008,
      "name": "bpf_trace_run6",
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701360,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701360,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647568,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647568,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692608,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692608,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
```

```json
{
  "name": "bpf_trace_run6",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755072,
      "name": "bpf_trace_run6",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1376",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:__bpf_trace_xdp_redirect_template",
        "mm/oom_kill.c:__bpf_trace_compact_retry",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_shrink_inactive",
        "mm/vmscan.c:__bpf_trace_mm_shrink_slab_end",
        "mm/slab_common.c:__bpf_trace_kmem_alloc_node",
        "mm/compaction.c:__bpf_trace_mm_compaction_end",
        "fs/ext4/super.c:__bpf_trace_ext4_fsmap_class",
        "fs/ext4/super.c:__bpf_trace_ext4_ext_remove_space_done",
        "fs/ext4/super.c:__bpf_trace_ext4_find_delalloc_range",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_extend",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_activate",
        "drivers/net/phy/mdio_bus.c:__bpf_trace_mdio_access",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_read",
        "drivers/thermal/thermal_core.c:__bpf_trace_thermal_power_devfreq_get_power",
        "drivers/ras/ras.c:__bpf_trace_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755072,
      "name": "bpf_trace_run6",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
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
void bpf_trace_run6(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5)
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
