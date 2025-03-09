# Function: <code>sched_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579074160,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:323",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:cpu_clock",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "block/blk-core.c:blk_rq_init",
        "block/blk-mq.c:__blk_mq_alloc_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074160,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579072413,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:324",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "block/blk-core.c:blk_dequeue_request",
        "block/blk-core.c:blk_rq_init",
        "block/blk-mq.c:__blk_mq_alloc_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070576,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579071789,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:325",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "block/blk-core.c:blk_dequeue_request",
        "block/blk-core.c:blk_rq_init",
        "block/blk-mq.c:__blk_mq_alloc_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069872,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579063757,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:225",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "block/blk-core.c:blk_dequeue_request",
        "block/blk-core.c:blk_rq_init",
        "block/blk-mq.c:blk_mq_get_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061872,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579072797,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:225",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "block/blk-core.c:blk_start_request",
        "block/blk-core.c:blk_rq_init",
        "block/blk-mq.c:blk_mq_get_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070928,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579076685,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:226",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075024,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081405,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:update_stats",
        "kernel/sched/psi.c:group_init",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579080976,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579091085,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090592,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579093069,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092576,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579104829,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:250",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579104336,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579105021,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:250",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579104528,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111549,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:251",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111040,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136489,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:251",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_tick_stable",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135968,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579172853,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:251",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:group_init",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_local",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172256,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579227077,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:251",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:group_init",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_local",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226416,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232613,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:279",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:psi_rtpoll_work",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:group_init",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf",
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231952,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579261461,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:279",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/build_policy.c:kcpustat_cpu_fetch",
        "kernel/sched/build_policy.c:kcpustat_field_vtime",
        "kernel/sched/build_policy.c:kcpustat_field_vtime",
        "kernel/sched/build_policy.c:task_gtime",
        "kernel/sched/build_policy.c:vtime_init_idle",
        "kernel/sched/build_policy.c:vtime_task_switch_generic",
        "kernel/sched/build_policy.c:vtime_account_kernel",
        "kernel/sched/build_policy.c:get_vtime_delta",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:psi_rtpoll_work",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/sched/build_utility.c:group_init",
        "kernel/sched/build_utility.c:sched_debug_header",
        "kernel/sched/build_utility.c:sched_clock_tick_stable",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_cpu",
        "kernel/sched/build_utility.c:sched_clock_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:uprobe_prog_run",
        "kernel/trace/bpf_trace.c:uprobe_prog_run",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/trampoline.c:__bpf_prog_exit",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_exit_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/netkit.c:netkit_xmit",
        "drivers/net/netkit.c:netkit_xmit",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf",
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf",
        "net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4",
        "net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6",
        "net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260816,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490937536,
      "name": "sched_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:64",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/trace.c:tracing_log_err",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/perf/arm_pmu.c:armpmu_dispatch_irq",
        "drivers/perf/arm_pmu.c:armpmu_dispatch_irq",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491419000,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224955808,
      "name": "sched_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:64",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "arch/arm/mach-omap2/pm-debug.c:pwrdms_setup",
        "arch/arm/mach-omap2/pm-debug.c:pm_dbg_update_time",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/trace.c:tracing_log_err",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic",
        "drivers/perf/arm_pmu.c:armpmu_dispatch_irq",
        "drivers/perf/arm_pmu.c:armpmu_dispatch_irq",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225411964,
      "name": "sched_clock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282343552,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/powerpc/kernel/time.c:722",
      "file": "arch/powerpc/kernel/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/time.c:running_clock"
      ],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "arch/powerpc/perf/core-book3s.c:perf_event_interrupt",
        "arch/powerpc/perf/core-book3s.c:perf_event_interrupt",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/printk/printk.c:cont_add",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/trace.c:tracing_log_err",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle",
        "drivers/cpuidle/governors/teo.c:teo_reflect",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282343392,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271570106,
      "name": "sched_clock",
      "external": true,
      "loc": "kernel/sched/clock.c:64",
      "file": "kernel/sched/clock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:trace_initcall_finish_cb",
        "init/main.c:trace_initcall_start_cb",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:running_clock",
        "kernel/sched/clock.c:sched_clock_cpu",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:proc_sched_show_task",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:collect_percpu_times",
        "kernel/sched/psi.c:group_init",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/trace.c:tracing_log_err",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_read",
        "kernel/events/core.c:cpu_clock_event_add",
        "kernel/events/core.c:cpu_clock_event_stop",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:__perf_event_account_interrupt",
        "kernel/events/core.c:calc_timer_values",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:ctx_sched_in",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:ctx_sched_out",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_event_disable",
        "kernel/events/core.c:__perf_remove_from_context",
        "kernel/events/core.c:__perf_remove_from_context",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_busy_loop_end",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/sock.c:sk_busy_loop_end",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_bpf_run",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271886642,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579093421,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092928,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025415,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/cputime.c:task_gtime",
        "kernel/sched/cputime.c:vtime_init_idle",
        "kernel/sched/cputime.c:arch_vtime_task_switch",
        "kernel/sched/cputime.c:get_vtime_delta",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579025072,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579093005,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092512,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long long unsigned int sched_clock()
```

```json
{
  "name": "sched_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579097245,
      "name": "sched_clock",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:243",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:tsc_save_sched_clock_state"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/events/amd/ibs.c:perf_ibs_nmi_handler",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/nmi.c:nmi_handle",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/clock.c:sched_clock_local",
        "kernel/sched/clock.c:__sched_clock_gtod_offset",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/sched/psi.c:group_init",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/trace_clock.c:trace_clock_local",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cached",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096752,
      "name": "sched_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long long unsigned int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
