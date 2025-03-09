# Function: <code>__percpu_add_case_32</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __percpu_add_case_32(void * ptr, long unsigned int val)
```

```json
{
  "name": "__percpu_add_case_32",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491115784,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491167656,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:__printk_safe_exit",
        "kernel/printk/printk_safe.c:__printk_safe_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491865136,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:put_trace_buf",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_nostack",
        "kernel/trace/trace.c:disable_trace_buffered_event",
        "kernel/trace/trace.c:enable_trace_buffered_event"
      ],
      "caller_func": [
        "kernel/trace/trace.c:tracing_mark_raw_write",
        "kernel/trace/trace.c:tracing_mark_write",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:__ftrace_trace_stack",
        "kernel/trace/trace.c:trace_function",
        "kernel/trace/trace.c:trace_buffer_unlock_commit_regs",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace.c:trace_event_buffer_lock_reserve"
      ]
    },
    {
      "addr": 18446603336491983112,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_syscalls.c:ftrace_syscall_exit",
        "kernel/trace/trace_syscalls.c:ftrace_syscall_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492047376,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp",
        "kernel/trace/bpf_trace.c:put_bpf_raw_tp_regs",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output_tp",
        "kernel/trace/bpf_trace.c:bpf_event_output",
        "kernel/trace/bpf_trace.c:bpf_perf_event_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492062636,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492099468,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492137700,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492281660,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_free",
        "kernel/bpf/devmap.c:dev_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492296488,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_prog_offload_init",
        "kernel/bpf/offload.c:bpf_prog_offload_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492362764,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_sched_cb_inc",
        "kernel/events/core.c:perf_sched_cb_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492507520,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493532860,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_fsmount",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:__arm64_sys_open_tree",
        "fs/namespace.c:umount_tree",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mntput_no_expire",
        "fs/namespace.c:mnt_change_mountpoint",
        "fs/namespace.c:mnt_set_mountpoint",
        "fs/namespace.c:mnt_drop_write_file",
        "fs/namespace.c:mnt_drop_write",
        "fs/namespace.c:mnt_clone_write",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:__mnt_want_write",
        "fs/namespace.c:alloc_vfsmnt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493662276,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:buffer_exit_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493785488,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "fs/eventfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventfd.c:eventfd_signal",
        "fs/eventfd.c:eventfd_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495164612,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_node_kill",
        "security/selinux/avc.c:avc_node_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495235216,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "security/selinux/netif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/netif.c:sel_netif_sid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495363004,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "security/lsm_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:dump_common_audit_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496011432,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496311224,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "lib/percpu_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu_counter.c:percpu_counter_add_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499973428,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_chr_show_fdinfo",
        "drivers/net/tun.c:tun_chr_show_fdinfo",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:tun_peek_len",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_chr_read_iter",
        "drivers/net/tun.c:tun_chr_read_iter",
        "drivers/net/tun.c:tun_chr_write_iter",
        "drivers/net/tun.c:tun_chr_write_iter",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_chr_poll",
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501866580,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502048568,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_getfirstbyhwtype",
        "net/core/dev.c:dev_get_by_index",
        "net/core/dev.c:dev_get_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502070172,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502086012,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_dev_put",
        "net/core/dst.c:dst_dev_put",
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502103256,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:neigh_parms_alloc",
        "net/core/neighbour.c:pneigh_enqueue",
        "net/core/neighbour.c:neigh_proxy_process",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:pneigh_delete",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:pneigh_lookup",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/neighbour.c:pneigh_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502162412,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/utils.c:inet6_pton"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502164020,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:linkwatch_fire_event",
        "net/core/link_watch.c:linkwatch_do_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502263880,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:netdev_queue_update_kobjects",
        "net/core/net-sysfs.c:netdev_queue_release",
        "net/core/net-sysfs.c:net_rx_queue_update_kobjects",
        "net/core/net-sysfs.c:rx_queue_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502282924,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_cleanup",
        "net/core/netpoll.c:netpoll_setup",
        "net/core/netpoll.c:netpoll_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502327568,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_hw_packet_probe",
        "net/core/drop_monitor.c:net_dm_hw_metadata_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502334148,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/netprio_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netprio_cgroup.c:write_priomap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502342052,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:bpf_input",
        "net/core/lwt_bpf.c:bpf_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502412984,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502453044,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:qdisc_destroy",
        "net/sched/sch_generic.c:qdisc_alloc",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:pfifo_fast_dequeue",
        "net/sched/sch_generic.c:__netdev_watchdog_up",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502462884,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_dump_tclass",
        "net/sched/sch_api.c:qdisc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502523616,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/netlink/af_netlink.c:netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502565712,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_get_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs",
        "net/netfilter/nf_queue.c:nf_queue_entry_release_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502595744,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_blackhole_route",
        "net/ipv4/route.c:rt_flush_dev",
        "net/ipv4/route.c:rt_flush_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502644120,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502906708,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:inetdev_init",
        "net/ipv4/devinet.c:in_dev_finish_destroy",
        "net/ipv4/devinet.c:__ip_dev_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502967784,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_check_nh",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v4_gw",
        "net/ipv4/fib_semantics.c:fib_check_nh_v6_gw",
        "net/ipv4/fib_semantics.c:fib_nh_common_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502986220,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/fib_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:fib_table_lookup",
        "net/ipv4/fib_trie.c:resize",
        "net/ipv4/fib_trie.c:resize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503056076,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv4/ipmr.c:ipmr_new_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503096712,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv4/xfrm4_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/xfrm4_policy.c:xfrm4_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503109728,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_dst_ifdown",
        "net/xfrm/xfrm_policy.c:xfrm_dst_ifdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503146040,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503176112,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503189808,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add",
        "net/xfrm/xfrm_device.c:xfrm_dev_state_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503297004,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:inet6_rtm_getaddr",
        "net/ipv6/addrconf.c:inet6_netconf_get_devconf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503357860,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:rt6_disable_ip",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:ip6_route_check_nh",
        "net/ipv6/route.c:rt6_probe_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503391924,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503551572,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mif6_delete",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:pim6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503561172,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503603008,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ipv6/addrconf_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf_core.c:in6_dev_finish_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503635700,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_notifier",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_do_bind",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_destruct_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503693212,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503738636,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/switchdev/switchdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/switchdev/switchdev.c:switchdev_deferred_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503771996,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-netlink.c:ndp_from_ifindex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503782236,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_bind",
        "net/xdp/xsk.c:xsk_unbind_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503791736,
      "name": "__percpu_add_case_32",
      "external": false,
      "loc": "arch/arm64/include/asm/percpu.h:112",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_clear_dev",
        "net/xdp/xdp_umem.c:xdp_umem_assign_dev"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491851600,
      "name": "__percpu_add_case_32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __percpu_add_case_32(void * ptr, long unsigned int val)
```
</details>
</li>
</ul>
