# Function: <code>get_random_u32</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777504,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2130",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "mm/slub.c:new_slab",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777504,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585197616,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2129",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "mm/slub.c:new_slab",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197616,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585433904,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2237",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "mm/slub.c:new_slab",
        "lib/rhashtable.c:bucket_table_alloc",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433904,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557328,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2262",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_constants",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:new_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557328,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777904,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2343",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777904,
      "name": "get_random_u32",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585920608,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920608,
      "name": "get_random_u32",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653520,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2215",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vdso_addr",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "lib/nodemask.c:node_random",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653520,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764224,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2214",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:vdso_addr",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "lib/nodemask.c:node_random",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764224,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586645360,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2190",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "lib/nodemask.c:node_random",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645360,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192832,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2215",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "lib/nodemask.c:node_random",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192832,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500240,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:510",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:arch_setup_additional_pages",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "mm/shmem.c:shmem_get_inode",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/slub.c:allocate_slab",
        "mm/kfence/core.c:kfence_guarded_alloc",
        "mm/migrate.c:next_demotion_node",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/fat/inode.c:fat_fill_inode",
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node",
        "lib/nodemask.c:node_random",
        "net/core/sock.c:sock_setsockopt",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_output.c:ip_build_and_send_pkt",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack",
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/icmp.c:icmp_global_allow",
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi",
        "net/unix/af_unix.c:unix_autobind",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/route.c:rt6_insert_exception",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500240,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589935616,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:532",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/mm/cpu_entry_area.c:init_cea_offsets",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "mm/shmem.c:shmem_get_inode",
        "mm/kfence/core.c:kfence_init",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/fat/inode.c:fat_fill_inode",
        "drivers/char/random.c:__get_random_u32_below",
        "drivers/char/random.c:__get_random_u32_below",
        "net/core/sock.c:sk_setsockopt",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_plb.c:tcp_plb_check_rehash",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/unix/af_unix.c:unix_autobind",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/output_core.c:ipv6_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589935616,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590245616,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:532",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/mm/cpu_entry_area.c:init_cea_offsets",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "mm/shmem.c:shmem_get_inode",
        "mm/kfence/core.c:kfence_init",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/fat/inode.c:fat_fill_inode",
        "drivers/char/random.c:__get_random_u32_below",
        "drivers/char/random.c:__get_random_u32_below",
        "net/core/sock.c:sk_setsockopt",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_plb.c:tcp_plb_check_rehash",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/unix/af_unix.c:unix_autobind",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/syncookies.c:cookie_v6_check",
        "net/ipv6/output_core.c:ipv6_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590245616,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590586640,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:532",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/mm/cpu_entry_area.c:init_cea_offsets",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/bloom_filter.c:bloom_map_alloc",
        "mm/shmem.c:__shmem_get_inode",
        "mm/kfence/core.c:kfence_init",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/fat/inode.c:fat_fill_inode",
        "drivers/char/random.c:__get_random_u32_below",
        "drivers/char/random.c:__get_random_u32_below",
        "net/core/sock.c:sk_setsockopt",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans",
        "net/ipv4/tcp_output.c:tcp_rtx_synack",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_plb.c:tcp_plb_check_rehash",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/unix/af_unix.c:unix_autobind",
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/datagram.c:__ip6_datagram_connect",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get",
        "net/ipv6/output_core.c:ipv6_select_ident"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590586640,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498741872,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:arch_align_stack",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498741872,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231360824,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/process.c:arch_setup_additional_pages",
        "arch/arm/kernel/signal.c:get_signal_page",
        "kernel/fork.c:copy_process",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/util.c:arch_pick_mmap_layout",
        "mm/util.c:randomize_stack_top",
        "mm/slab_common.c:cache_random_seq_create",
        "mm/shuffle.c:__shuffle_zone",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:allocate_slab",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/random.c:randomize_page",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231360824,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291896416,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/process.c:arch_align_stack",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291896416,
      "name": "get_random_u32",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276243444,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276243444,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681584,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681584,
      "name": "get_random_u32",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541456,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541456,
      "name": "get_random_u32",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585871008,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871008,
      "name": "get_random_u32",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
u32 get_random_u32()
```

```json
{
  "name": "get_random_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978912,
      "name": "get_random_u32",
      "external": true,
      "loc": "drivers/char/random.c:2404",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_randomized",
        "arch/x86/kernel/process.c:arch_align_stack",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/module.c:module_alloc",
        "kernel/bpf/core.c:bpf_jit_blind_insn",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/slub.c:allocate_slab",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/ipv4/route.c:rt_genid_init",
        "lib/nodemask.c:node_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978912,
      "name": "get_random_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u32 get_random_u32()
```
</details>
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
