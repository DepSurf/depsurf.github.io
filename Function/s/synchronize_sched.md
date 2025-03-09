# Function: <code>synchronize_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_sched()
```

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787968,
      "name": "synchronize_sched",
      "external": true,
      "loc": "kernel/rcu/tree.c:3201",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/cpu.c:_cpu_down",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/sync.c:synchronize_rcu",
        "kernel/rcu/tree.c:cond_synchronize_sched",
        "kernel/module.c:free_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/trace.c:tracing_reset",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/padata.c:padata_replace",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:replace_mount_options",
        "fs/namespace.c:namespace_unlock",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/mousedev.c:mousedev_detach_client",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/i2c/i2c-core.c:i2c_exit",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/netfilter/core.c:nf_unregister_afinfo",
        "net/netfilter/nf_log.c:nf_log_unset",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/netfilter/nf_queue.c:nf_unregister_queue_handler",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787968,
      "name": "synchronize_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void synchronize_sched()
```

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579808512,
      "name": "synchronize_sched",
      "external": true,
      "loc": "kernel/rcu/tree.c:3279",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:synchronize_rcu",
        "kernel/rcu/tree.c:cond_synchronize_sched",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_reset",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
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
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/zswap.c:__zswap_pool_release",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:replace_mount_options",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_detach_client",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/i2c/i2c-core.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/netfilter/core.c:nf_unregister_afinfo",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/netfilter/nf_log.c:nf_log_unset",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/fib_trie.c:tnode_free",
        "net/xfrm/xfrm_policy.c:xfrm_policy_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo",
        "net/xfrm/xfrm_state.c:xfrm_unregister_km",
        "net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo",
        "net/ipv6/raw.c:rawv6_mh_filter_unregister",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6",
        "net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808512,
      "name": "synchronize_sched.part.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579812960,
      "name": "synchronize_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_sched()
```

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579848048,
      "name": "synchronize_sched",
      "external": true,
      "loc": "kernel/rcu/tree.c:3277",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:synchronize_rcu",
        "kernel/rcu/tree.c:cond_synchronize_sched",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_reset",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
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
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:namespace_unlock",
        "fs/namespace.c:replace_mount_options",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_detach_client",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/i2c/i2c-core.c:i2c_exit",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/netfilter/core.c:nf_unregister_afinfo",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/netfilter/nf_log.c:nf_log_unset",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/fib_trie.c:tnode_free",
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
      "addr": 18446744071579848048,
      "name": "synchronize_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_sched()
```

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851440,
      "name": "synchronize_sched",
      "external": true,
      "loc": "kernel/rcu/tree.c:3297",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:synchronize_rcu",
        "kernel/rcu/tree.c:cond_synchronize_rcu",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_init_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/kprobes.c:collect_garbage_slots",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:clear_ftrace_pids",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare_sync",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_reset_online_cpus",
        "kernel/trace/trace.c:tracing_reset",
        "kernel/trace/blktrace.c:blk_unregister_tracepoints",
        "kernel/trace/trace_events.c:event_trace_del_tracer",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "kernel/membarrier.c:SyS_membarrier",
        "mm/swap_state.c:exit_swap_address_space",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:namespace_unlock",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/scsi/scsi.c:scsi_attach_vpd",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_detach_client",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
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
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/netfilter/core.c:nf_unregister_afinfo",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
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
      "addr": 18446744071579851440,
      "name": "synchronize_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_sched()
```

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579891888,
      "name": "synchronize_sched",
      "external": true,
      "loc": "kernel/rcu/tree.c:3280",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:SyS_membarrier",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:synchronize_rcu",
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
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_filter.c:apply_event_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:trigger_data_free",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_register",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/sockmap.c:sock_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:SYSC_perf_event_open",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "kernel/memremap.c:pgmap_radix_release",
        "mm/swap_state.c:exit_swap_address_space",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/file.c:expand_files",
        "fs/filesystems.c:unregister_filesystem",
        "fs/namespace.c:namespace_unlock",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:__sysrq_swap_key_ops",
        "drivers/iommu/dmar.c:dmar_hp_release_drhd",
        "drivers/iommu/intel-iommu.c:dmar_release_one_atsr",
        "drivers/scsi/scsi_lib.c:scsi_device_quiesce",
        "drivers/input/input.c:input_unregister_handle",
        "drivers/input/input.c:input_close_device",
        "drivers/input/input.c:input_open_device",
        "drivers/input/input.c:__input_release_device",
        "drivers/input/mousedev.c:mousedev_detach_client",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_do_ioctl",
        "drivers/input/evdev.c:evdev_release",
        "drivers/input/evdev.c:evdev_detach_client",
        "drivers/i2c/i2c-core-base.c:i2c_exit",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/edac/edac_mc.c:edac_mc_del_mc",
        "drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups",
        "drivers/edac/edac_device.c:edac_device_del_device",
        "drivers/edac/edac_pci.c:edac_pci_del_device",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_clear_update_util_hook",
        "drivers/cpuidle/cpuidle.c:cpuidle_uninstall_idle_handler",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_delete",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/dev.c:synchronize_net",
        "net/core/dev.c:dev_change_name",
        "net/core/rtnetlink.c:rtnl_af_unregister",
        "net/netfilter/core.c:nf_unregister_afinfo",
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
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
      "addr": 18446744071579891888,
      "name": "synchronize_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void synchronize_sched()
```

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579923008,
      "name": "synchronize_sched",
      "external": true,
      "loc": "kernel/rcu/tree.c:3086",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:unregister_nmi_handler",
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "arch/x86/mm/mmio-mod.c:mmiotrace_iounmap",
        "kernel/notifier.c:atomic_notifier_chain_unregister",
        "kernel/sched/cpufreq_schedutil.c:sugov_stop",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_global_expedited",
        "kernel/printk/printk.c:kmsg_dump_unregister",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/sync.c:synchronize_rcu",
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
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:array_map_free",
        "kernel/bpf/lpm_trie.c:trie_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/cpumap.c:cpu_map_free",
        "kernel/bpf/sockmap.c:sock_hash_free",
        "kernel/bpf/sockmap.c:sock_map_free",
        "kernel/bpf/stackmap.c:stack_map_free",
        "kernel/events/core.c:perf_pmu_migrate_context",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/padata.c:padata_replace",
        "kernel/memremap.c:pgmap_radix_release",
        "mm/swap_state.c:exit_swap_address_space",
        "mm/zswap.c:__zswap_pool_release",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_unregister_event",
        "mm/memcontrol.c:__mem_cgroup_usage_register_event",
        "fs/namespace.c:namespace_unlock",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/eventpoll.c:ep_destroy_wakeup_source",
        "security/keys/gc.c:key_garbage_collector",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/apparmor/policy.c:__replace_profile",
        "security/integrity/ima/ima_policy.c:ima_update_policy",
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "drivers/acpi/apei/ghes.c:ghes_remove",
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
        "net/netfilter/nf_log.c:nf_log_unregister",
        "net/ipv4/tcp_cong.c:tcp_unregister_congestion_control",
        "net/ipv4/tcp_ulp.c:tcp_unregister_ulp",
        "net/ipv4/fib_trie.c:tnode_free",
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
      "addr": 18446744071579923008,
      "name": "synchronize_sched",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "synchronize_sched",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579818824,
      "name": "synchronize_sched",
      "external": false,
      "loc": "include/linux/rcupdate.h:922",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpufreq_schedutil.c:sugov_stop"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void synchronize_sched()
```
</details>
</li>
</ul>
