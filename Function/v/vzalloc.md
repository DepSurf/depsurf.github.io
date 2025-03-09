# Function: <code>vzalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742544,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1759",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "security/apparmor/lib.c:__aa_kvmalloc",
        "block/partitions/check.c:check_partition",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742544,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862288,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1780",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "kernel/bpf/stackmap.c:stack_map_alloc",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "security/apparmor/lib.c:__aa_kvmalloc",
        "block/partitions/check.c:check_partition",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862288,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932592,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1793",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_analyzer",
        "kernel/bpf/verifier.c:bpf_check",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "security/apparmor/lib.c:__aa_kvmalloc",
        "block/partitions/check.c:check_partition",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/dev.c:alloc_netdev_mqs",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932592,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976624,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1863",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_analyzer",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:SyS_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "block/partitions/check.c:check_partition",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976624,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581079248,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1855",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "block/partitions/check.c:check_partition",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079248,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218272,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1842",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218272,
      "name": "vzalloc",
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301904,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1848",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301904,
      "name": "vzalloc",
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379104,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2602",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/input/evdev.c:evdev_open",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379104,
      "name": "vzalloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440304,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440304,
      "name": "vzalloc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648656,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2639",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_purgatory_setup_kbuf",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:adjust_insn_aux_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:zlib_deflate_alloc_ctx",
        "crypto/deflate.c:deflate_alloc_ctx",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/md/dm-table.c:setup_indexes",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ethtool/ioctl.c:ethtool_get_strings",
        "net/ethtool/ioctl.c:ethtool_get_regs",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648656,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695040,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2672",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_purgatory_setup_kbuf",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:adjust_insn_aux_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:zlib_deflate_alloc_ctx",
        "crypto/deflate.c:deflate_alloc_ctx",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/md/dm-table.c:setup_indexes",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ethtool/ioctl.c:ethtool_get_strings",
        "net/ethtool/ioctl.c:ethtool_get_regs",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695040,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716896,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3036",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/relay.c:relay_create_buf",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:adjust_insn_aux_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:zlib_deflate_alloc_ctx",
        "crypto/deflate.c:deflate_alloc_ctx",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ethtool/ioctl.c:ethtool_get_strings",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716896,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989136,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3142",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/relay.c:relay_create_buf",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:zlib_deflate_alloc_ctx",
        "crypto/deflate.c:deflate_alloc_ctx",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ethtool/ioctl.c:ethtool_get_strings",
        "net/ethtool/ioctl.c:ethtool_get_regs",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989136,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413392,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3302",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate",
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/relay.c:relay_alloc_buf",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ethtool/ioctl.c:ethtool_get_strings",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413392,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921040,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3364",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate",
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_vzalloc_stats_array",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921040,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137200,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3457",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137200,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320320,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3457",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:prepare_elf_headers",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/profile.c:profile_init",
        "kernel/crash_core.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_purgatory_setup_sechdrs",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_init",
        "crypto/deflate.c:deflate_alloc_ctx",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/core.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/char/agp/backend.c:agp_backend_initialize",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_helper_fb_probe",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_get_dump_data",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:ethtool_get_stats",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320320,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492843968,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/arm.c:kvm_arch_alloc_vm",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/soc/fsl/qbman/qman.c:qman_alloc_fq_table",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492843968,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226650332,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs",
        "kernel/profile.c:profile_init",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226650332,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286232544,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc",
        "arch/powerpc/platforms/powernv/opal-flash.c:image_data_write",
        "arch/powerpc/platforms/powernv/opal-dump.c:dump_attr_read",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286232544,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272795356,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:profile_init",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272795356,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
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
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409152,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409152,
      "name": "vzalloc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351184,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351184,
      "name": "vzalloc",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400352,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400352,
      "name": "vzalloc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * vzalloc(long unsigned int size)
```

```json
{
  "name": "vzalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463856,
      "name": "vzalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2610",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/profile.c:profile_init",
        "kernel/kexec_file.c:crash_prepare_elf64_headers",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_load_purgatory",
        "kernel/kexec_file.c:kexec_calculate_store_digests",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/trace/trace.c:trace_pid_write",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:bpf_patch_insn_data",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swap_cgroup.c:swap_cgroup_swapon",
        "fs/proc/vmcore.c:vmcore_add_device_dump",
        "crypto/deflate.c:deflate_decomp_init",
        "crypto/deflate.c:deflate_comp_init",
        "block/partitions/check.c:check_partition",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/backend.c:agp_add_bridge",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/ipv4/fib_trie.c:tnode_new",
        "net/xfrm/xfrm_hash.c:xfrm_hash_alloc",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463856,
      "name": "vzalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
