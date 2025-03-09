# Function: <code>synchronize_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579051753,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322082,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375135,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:_cpu_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506242,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724816,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776736,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/rcu/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580382513,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385517,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390671,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458889,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923980,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118790,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:unregister_filesystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581121197,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:replace_mount_options",
        "fs/namespace.c:namespace_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189028,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_umount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289046,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_destroy_wakeup_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183712,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405134,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512381,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748054,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583783910,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584013538,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241789,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584298779,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_hp_release_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584323235,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584463338,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585558258,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:__input_release_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_unregister_handle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585576757,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585582904,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716871,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905730,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149282,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586176794,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586254253,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586263150,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586276455,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586516948,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/netfilter/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586520760,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_unset",
        "net/netfilter/nf_log.c:nf_log_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586522900,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_unregister_queue_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586710275,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586835371,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:tnode_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586910913,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586936449,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586953044,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123300,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_mh_filter_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587286014,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:310",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776736,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579047999,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328305,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520354,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579576770,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579745840,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579802112,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/rcu/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580445301,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448559,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580451181,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580483852,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580534409,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901127,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070640,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284518,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:unregister_filesystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287445,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:replace_mount_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352468,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_umount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454966,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_destroy_wakeup_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399945,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582626569,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747885,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582868259,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_update_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026054,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584109960,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584344418,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648557,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_hp_release_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584670067,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799850,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585135359,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/scsi/scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585952652,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585970677,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585984511,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586145468,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586305298,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562114,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586597418,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586678495,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586689153,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586702151,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959364,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/netfilter/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586963364,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/netfilter/nf_log.c:nf_log_unset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157987,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587285771,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:tnode_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587357202,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587383110,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587399286,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574596,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_mh_filter_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753846,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802112,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579047055,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343633,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579544002,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602866,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579774544,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830464,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/rcu/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580497909,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580505839,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512317,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549397,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599461,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969011,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146016,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362934,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:unregister_filesystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366309,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:replace_mount_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431380,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_umount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535750,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_destroy_wakeup_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492133,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719993,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843053,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964723,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_update_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583130918,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583175532,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584257912,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526258,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584834605,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_hp_release_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584857203,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991802,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585329503,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/scsi/scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141052,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586159013,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586172111,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586348293,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586513138,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586743730,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586781866,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586862850,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586875092,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888519,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587154068,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/netfilter/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587158244,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/netfilter/nf_log.c:nf_log_unset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356947,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587487115,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:tnode_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587560082,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587585622,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587602518,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587778884,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_mh_filter_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587969062,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:319",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830464,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579039404,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337668,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530562,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579770688,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830432,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/rcu/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579851589,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:cond_synchronize_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580158569,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580527637,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580535647,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544173,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581139,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629493,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992987,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:exit_swap_address_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018067,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195104,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418358,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:unregister_filesystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421285,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:namespace_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485557,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_umount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588630,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_destroy_wakeup_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582573066,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811641,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923072,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583014995,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_update_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583185936,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583249492,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334459,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584609758,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924333,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_hp_release_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584946339,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585414975,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/scsi/scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586229836,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586247941,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586260395,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447993,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562345,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586568720,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_del_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586576720,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_del_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586638770,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870962,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586902922,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586986341,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999644,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587012823,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587286212,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/netfilter/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587289332,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587489907,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587503859,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587624315,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:tnode_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587706405,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587732144,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587749424,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935540,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_mh_filter_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588127210,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:94",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830432,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579047596,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363092,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557058,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803680,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870528,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/rcu/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579892037,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:cond_synchronize_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580211465,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580591141,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599807,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608296,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580611378,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615170,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580620885,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:sock_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580621853,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580660867,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710533,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580716445,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:pgmap_radix_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097291,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:exit_swap_address_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127139,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325040,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559926,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:unregister_filesystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562789,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:namespace_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627701,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_umount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732486,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_destroy_wakeup_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725803,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968457,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082288,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583180019,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_update_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363312,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583428660,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584738793,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022286,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585345661,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_hp_release_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585367667,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872378,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586693164,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586711413,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586723803,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884384,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029865,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587035776,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_del_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587043808,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_del_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587120306,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358994,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394762,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587484709,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587498292,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587510775,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603418,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_af_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587806372,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/netfilter/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/core.c:nf_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810772,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588012227,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588026307,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588148715,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:tnode_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588233093,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259072,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277440,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588470996,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_mh_filter_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588675034,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870528,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579052332,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375429,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579585330,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/notifier.c:atomic_notifier_chain_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837152,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904704,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/rcu/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579923191,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:cond_synchronize_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271366,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/kprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580611729,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:trace_uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580686949,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697029,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703845,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/lpm_trie.c:trie_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720741,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722245,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580737141,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:sock_hash_free",
        "kernel/bpf/sockmap.c:sock_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580748245,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791711,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842197,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848942,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:pgmap_radix_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238107,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:exit_swap_address_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268927,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_pool_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471312,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717014,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581718933,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:namespace_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786352,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_umount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900214,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_destroy_wakeup_source"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924278,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169323,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/smack/smackfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285056,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386708,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "security/integrity/ima/ima_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_policy.c:ima_update_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583571124,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583639895,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584967425,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585256627,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587869,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_hp_release_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585610099,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118346,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959596,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586981741,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990059,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/input/evdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587193258,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587328153,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334112,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_del_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342224,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_del_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419843,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587662690,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695338,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587789992,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587803185,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587814830,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587912842,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/core/rtnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_af_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588153396,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588363811,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377539,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv4/tcp_ulp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588502984,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:tnode_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588587389,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588614160,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588632464,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588834657,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_mh_filter_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589041562,
      "name": "synchronize_rcu",
      "external": false,
      "loc": "include/linux/rcupdate.h:92",
      "file": "net/netlabel/netlabel_domainhash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904704,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579971872,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:1119",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_reset",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/swap_state.c:exit_swap_address_space",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971872,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011712,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2667",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_reset",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages_release",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011712,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056176,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056176,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121984,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3422",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:iounmap_trace_core",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/rcu/update.c:rcu_tasks_postgp",
        "kernel/rcu/update.c:rcu_tasks_pregp_step",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:unregister_kretprobe",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/ringbuf.c:ringbuf_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:__padata_free",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_fdtable",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/super.c:handle_mount_opt",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:__register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netif_napi_del",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121984,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103104,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3732",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:iounmap_trace_core",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:__padata_set_cpumasks",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pageunmap_range",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_fdtable",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:add_new_gdb",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/super.c:handle_mount_opt",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_bridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:__register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:dev_change_net_namespace",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103104,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103216,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3777",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/super.c:handle_mount_opt",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103216,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243152,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3738",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:kvm_set_posted_intr_wakeup_handler",
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:modify_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:register_ftrace_direct",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:compat_blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/migrate.c:migrate_on_reclaim_callback",
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:handle_mount_opt",
        "fs/ext4/super.c:handle_mount_opt",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/socket.c:sock_unregister",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_offload",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243152,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580413920,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3834",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sugov_stop",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_trace_postscan",
        "kernel/rcu/update.c:rcu_tasks_postgp",
        "kernel/rcu/update.c:rcu_tasks_pregp_step",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:free_module",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:compat_blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/migrate.c:migrate_on_reclaim_callback",
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/super.c:__ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_update_rules",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_unregister",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/socket.c:sock_unregister",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:unregister_netdevice_many",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413920,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580646805,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3532",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:cond_synchronize_rcu_full",
        "kernel/rcu/tree.c:kvfree_call_rcu"
      ],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sugov_stop",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu_full",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:free_module",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/rv/rv.c:monitoring_on_write_data",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv_reactors.c:reacting_on_write_data",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/syscall.c:bpf_map_update_value",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/super.c:__ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/scsi/scsi_lib.c:scsi_host_block",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_unregister",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/socket.c:sock_unregister",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/devlink.c:devl_traps_unregister",
        "net/core/devlink.c:devl_traps_unregister",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "lib/logic_pio.c:logic_pio_unregister_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626448,
      "name": "synchronize_rcu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580640016,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715952,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3524",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sugov_stop",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu_full",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:free_module",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/rv/rv.c:monitoring_on_write_data",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv_reactors.c:reacting_on_write_data",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/syscall.c:bpf_map_update_value",
        "kernel/bpf/arraymap.c:prog_array_map_poke_run",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:kern_unmount",
        "fs/namespace.c:kern_unmount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/super.c:__ext4_remount",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:free_ipc",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "io_uring/io_uring.c:io_ring_exit_work",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_unregister",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_populate_hdev",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/socket.c:sock_unregister",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_pack",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_update_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/devlink/leftover.c:devl_traps_unregister",
        "net/devlink/leftover.c:devl_traps_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "lib/logic_pio.c:logic_pio_unregister_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715952,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580789792,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3596",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/kernel/reboot.c:cpu_emergency_unregister_virt_callback",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update",
        "kernel/notifier.c:unregister_die_notifier",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:sched_update_numa",
        "kernel/sched/build_utility.c:sugov_stop",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu_full",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_init_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:free_module",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/kprobes.c:unregister_kprobe",
        "kernel/kprobes.c:register_kprobe",
        "kernel/kprobes.c:register_aggr_kprobe",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_trampoline_free",
        "kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set",
        "kernel/trace/ring_buffer.c:ring_buffer_reset",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_open",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_filter.c:process_system_preds",
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:event_trigger_free",
        "kernel/trace/rv/rv.c:monitoring_on_write_data",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv_reactors.c:reacting_on_write_data",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/tcx.c:tcx_link_release",
        "kernel/bpf/tcx.c:tcx_link_release",
        "kernel/bpf/tcx.c:tcx_link_prog_attach",
        "kernel/bpf/tcx.c:tcx_link_prog_attach",
        "kernel/bpf/tcx.c:tcx_uninstall",
        "kernel/bpf/tcx.c:tcx_prog_detach",
        "kernel/bpf/tcx.c:tcx_prog_detach",
        "kernel/bpf/tcx.c:tcx_prog_attach",
        "kernel/bpf/tcx.c:tcx_prog_attach",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/padata.c:padata_cpu_dead",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/mmap_lock.c:free_memcg_path_bufs",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memory-tiers.c:memtier_hotplug_callback",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:kern_unmount",
        "fs/namespace.c:kern_unmount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/super.c:__ext4_remount",
        "fs/debugfs/file.c:debugfs_write_file_str",
        "ipc/namespace.c:free_ipc",
        "ipc/namespace.c:free_ipc",
        "security/keys/gc.c:key_garbage_collector",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:selinux_policy_commit",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "io_uring/io_uring.c:io_ring_exit_work",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/intel/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier",
        "drivers/iommu/intel/iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/gpu/drm/drm_file.c:drm_file_update_pid",
        "drivers/net/netkit.c:netkit_uninit",
        "drivers/net/netkit.c:netkit_link_attach",
        "drivers/net/netkit.c:netkit_link_release",
        "drivers/net/netkit.c:netkit_prog_detach",
        "drivers/net/netkit.c:netkit_prog_attach",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/ptp/ptp_vclock.c:ptp_vclock_unregister",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_device.c:edac_device_add_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/edac/edac_pci.c:edac_pci_add_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_cpu_offline",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpuidle/cpuidle.c:cpuidle_unregister",
        "drivers/cpuidle/cpuidle.c:cpuidle_pause",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_populate_hdev",
        "drivers/remoteproc/remoteproc_core.c:rproc_del",
        "net/socket.c:sock_unregister",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:unregister_netdevice_many_notify",
        "net/core/dev.c:free_netdev",
        "net/core/dev.c:netdev_rx_handler_unregister",
        "net/core/dev.c:netif_set_real_num_tx_queues",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_remove_pack",
        "net/core/dev.c:netdev_name_node_alt_destroy",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_update_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/tcp_ao.c:tcp_ao_del_cmd",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_unregister_translator",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/devlink/trap.c:devl_traps_unregister",
        "net/devlink/trap.c:devl_traps_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "lib/logic_pio.c:logic_pio_unregister_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789792,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491270128,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/debug-monitors.c:unregister_debug_hook",
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:enable_swap_info",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491270128,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225274376,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_reset_cpu",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_event_perf.c:perf_trace_event_unreg",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_detach_client",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225274376,
      "name": "synchronize_rcu",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284170032,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_event_perf.c:perf_trace_event_unreg",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:fd_array_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/misc/cxl/base.c:unregister_cxl_calls",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "net/socket.c:sock_unregister",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_bydst_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284170032,
      "name": "synchronize_rcu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271787576,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_event_perf.c:perf_trace_event_unreg",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_set_cpumask",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271787576,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580024912,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024912,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579966032,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966032,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016448,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/file.c:expand_files",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/netfilter/nfnetlink.c:nfnetlink_subsys_unregister",
        "net/netfilter/nfnetlink_queue.c:nfnl_queue_net_exit_batch",
        "net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_unregister",
        "net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_unregister",
        "net/netfilter/nf_conntrack_extend.c:nf_ct_extend_unregister",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_exit",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_net_exit_batch",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016448,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_rcu()
```

```json
{
  "name": "synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580064096,
      "name": "synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2727",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:rcu_sync_enter",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove",
        "kernel/trace/blktrace.c:put_probe_ref",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_probe.c:trace_probe_remove_file",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/queue_stack_maps.c:queue_stack_map_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/bpf/reuseport_array.c:reuseport_array_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_stop",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_replace",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "fs/ext4/resize.c:ext4_kvfree_array_rcu",
        "fs/ext4/super.c:ext4_remount",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "security/integrity/ima/ima_policy.c:ima_lsm_policy_change",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "lib/logic_pio.c:logic_pio_unregister_range",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_open",
        "drivers/input/mousedev.c:mousedev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_open",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_release",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:unregister_pernet_operations",
        "net/core/net_namespace.c:register_pernet_operations",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:setup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/core/netpoll.c:__netpoll_free",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_free",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/devlink.c:devlink_traps_unregister",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_init",
        "net/xfrm/xfrm_policy.c:xfrm_if_unregister_cb",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_policy.c:xfrm_hash_resize",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/xfrm/xfrm_state.c:xfrm_hash_resize",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064096,
      "name": "synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
