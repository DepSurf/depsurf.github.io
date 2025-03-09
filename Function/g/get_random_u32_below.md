# Function: <code>get_random_u32_below</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 get_random_u32_below(u32 ceil)
```

```json
{
  "name": "get_random_u32_below",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578865146,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:arch_setup_additional_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236075,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572559,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:init_cea_offsets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814007,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038962,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:node_random"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745986,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026323,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:set_cluster_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198698,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:shuffle_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232021,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267191,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584537790,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_group_orlov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584713355,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:ext4_multi_mount_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_register_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587906430,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401192,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593202145,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593364946,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593960417,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594109592,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594202238,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594213050,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594268633,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594424088,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/tcp_plb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_global_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594545470,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594827079,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595008882,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595030657,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_insert_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595184889,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ipv6_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595387306,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595171184,
      "name": "get_random_u32_below",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 get_random_u32_below(u32 ceil)
```

```json
{
  "name": "get_random_u32_below",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578863106,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:arch_setup_additional_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242059,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579584911,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:init_cea_offsets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580301636,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897303,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158971,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905650,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744303,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_rotate_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866742,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235951,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:set_cluster_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419290,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:shuffle_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583452453,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487543,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584766880,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_group_orlov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584937690,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:ext4_multi_mount_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_register_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177934,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588677096,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593662186,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593826786,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594337200,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594496393,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594589190,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594600193,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594654729,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594813400,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/tcp_plb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_global_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594937582,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595218589,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595402162,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595424100,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_insert_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595580576,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ipv6_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595783865,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595566736,
      "name": "get_random_u32_below",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 get_random_u32_below(u32 ceil)
```

```json
{
  "name": "get_random_u32_below",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578873618,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:arch_setup_additional_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270907,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_align_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579614703,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/module.c:module_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:init_cea_offsets"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354199,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:init_cfs_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987831,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_verify_choose_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264475,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029845,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582912075,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:lru_gen_online_memcg",
        "mm/vmscan.c:lru_gen_rotate_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583037958,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:cache_random_seq_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396522,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:shuffle_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472144,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:set_cluster_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583644021,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_guarded_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680423,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:next_demotion_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584999952,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:find_group_orlov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169258,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:ext4_multi_mount_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_register_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "crypto/rsa-pkcs1pad.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588468782,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_init_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977927,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pmem_find_many"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594439803,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594608386,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_proc_base_reachable_time",
        "net/core/neighbour.c:neightbl_set",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_periodic_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595136545,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595299353,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595392691,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_hash_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595403750,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595458794,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595624344,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/tcp_plb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_plb.c:tcp_plb_update_state_upon_rto"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_global_allow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595749820,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_heard_query",
        "net/ipv4/igmp.c:igmp_ifc_event",
        "net/ipv4/igmp.c:igmp_ifc_timer_expire",
        "net/ipv4/igmp.c:igmp_start_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596059133,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_alloc_spi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596243794,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_set_iftoken",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596265971,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_insert_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596423344,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:__mld_query_work"
      ]
    },
    {
      "addr": 0,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/ipv6/output_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/output_core.c:ipv6_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596633881,
      "name": "get_random_u32_below",
      "external": false,
      "loc": "include/linux/random.h:60",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596409584,
      "name": "get_random_u32_below",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
u32 get_random_u32_below(u32 ceil)
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
