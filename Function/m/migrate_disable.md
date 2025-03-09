# Function: <code>migrate_disable</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_disable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580571057,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853240,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939733,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032548,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581042900,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069760,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_prog_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133916,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817297,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589311701,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509910,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589546785,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:run_bpf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579992,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589644811,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589847637,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590905654,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590950984,
      "name": "migrate_disable",
      "external": false,
      "loc": "include/linux/preempt.h:335",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724592,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:1742",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_node",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724592,
      "name": "migrate_disable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731984,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:1750",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:bpf_for_each_hash_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_node",
        "kernel/bpf/arraymap.c:bpf_for_each_array_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_timer_continue",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731984,
      "name": "migrate_disable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812000,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:2128",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:bpf_for_each_hash_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_node",
        "kernel/bpf/arraymap.c:bpf_for_each_array_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_timer_continue",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812000,
      "name": "migrate_disable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927936,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:2224",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:bpf_for_each_hash_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:__htab_percpu_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_delete_node",
        "kernel/bpf/arraymap.c:bpf_for_each_array_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "mm/page_alloc.c:drain_local_pages_wq",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_timer_continue",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927936,
      "name": "migrate_disable",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079328,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:2216",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/syscall.c:bpf_map_update_value",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:bpf_for_each_hash_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:bpf_for_each_array_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_lsm_cgroup",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_free",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_timer_continue",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079328,
      "name": "migrate_disable",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133856,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:2391",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/trace_osnoise.c:timerlat_fd_release",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_open",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:osnoise_main",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/syscall.c:bpf_map_update_value",
        "kernel/bpf/helpers.c:bpf_rb_root_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:bpf_for_each_hash_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:bpf_for_each_array_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_lsm_cgroup",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_free",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cpumask.c:cpumask_free_cb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_timer_continue",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133856,
      "name": "migrate_disable",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void migrate_disable()
```

```json
{
  "name": "migrate_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580207408,
      "name": "migrate_disable",
      "external": true,
      "loc": "kernel/sched/core.c:2419",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/ring_buffer.c:ring_buffer_resize",
        "kernel/trace/trace_osnoise.c:timerlat_fd_release",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_open",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:osnoise_main",
        "kernel/trace/bpf_trace.c:uprobe_prog_run",
        "kernel/trace/bpf_trace.c:trace_call_bpf",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:generic_map_delete_batch",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:bpf_obj_free_fields",
        "kernel/bpf/syscall.c:bpf_map_copy_value",
        "kernel/bpf/syscall.c:bpf_map_update_value",
        "kernel/bpf/helpers.c:bpf_rb_root_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/hashtab.c:bpf_for_each_hash_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_free",
        "kernel/bpf/arraymap.c:bpf_for_each_array_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/trampoline.c:__bpf_prog_enter",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_sleepable_recur",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_lsm_cgroup",
        "kernel/bpf/trampoline.c:__bpf_prog_enter_recur",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_free",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cpumask.c:bpf_cpumask_release",
        "drivers/nvdimm/region_devs.c:nd_region_acquire_lane",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/sock_reuseport.c:reuseport_select_sock",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run_xdp_live",
        "net/bpf/test_run.c:bpf_test_timer_continue",
        "net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207408,
      "name": "migrate_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void migrate_disable()
```
</details>
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
