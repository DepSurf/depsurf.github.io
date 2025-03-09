# Function: <code>__bpf_prog_run</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int __bpf_prog_run(void * ctx, const struct bpf_insn * insn)
```

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357968,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "kernel/bpf/core.c:195",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357968,
      "name": "__bpf_prog_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5140
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
unsigned int __bpf_prog_run(void * ctx, const struct bpf_insn * insn)
```

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580414832,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "kernel/bpf/core.c:468",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580414832,
      "name": "__bpf_prog_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5138
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
unsigned int __bpf_prog_run(void * ctx, const struct bpf_insn * insn)
```

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463584,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "kernel/bpf/core.c:550",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463584,
      "name": "__bpf_prog_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5138
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580736908,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041305,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279033,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383798,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390840,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426715,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
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
      "addr": 18446744071581441162,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588343669,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588369446,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588407828,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589926712,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589993578,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_prog_run_generic_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590182445,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590189448,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:run_bpf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590299497,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590304683,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590409032,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559547,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721742,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590937422,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591539576,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591733576,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591749176,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591782356,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:606",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580949676,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299962,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432200,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573229,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706935,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712376,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752941,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782052,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589738934,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589767899,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589805164,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591459020,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591534154,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_prog_run_generic_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591744979,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591752295,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591883145,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591888663,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592000997,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592174960,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592350738,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592580338,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593229055,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593426695,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593455407,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593483098,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:609",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581245413,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626074,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:kprobe_multi_link_handler",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695892,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785368,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949832,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113443,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118884,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168045,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284240,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591373718,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591418142,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591460252,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593227095,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593307850,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_prog_run_generic_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593534691,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593542647,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593684809,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593690887,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593821002,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594003024,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594189826,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594442354,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595129183,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595340167,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595372479,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595401434,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581340372,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763525,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840835,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946532,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137640,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309523,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315060,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365197,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582487162,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591730634,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591753468,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_xdp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591833895,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591875772,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593687575,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593769555,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_prog_run_generic_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594002579,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594011719,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594165460,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594171687,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594195727,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594379296,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594485932,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/netfilter/nf_bpf_link.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594576929,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594832561,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595523564,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595735111,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595769644,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595797981,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:581",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_run",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581447380,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882277,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/bpf_trace.c:uprobe_prog_run",
        "kernel/trace/bpf_trace.c:bpf_trace_run12",
        "kernel/trace/bpf_trace.c:bpf_trace_run11",
        "kernel/trace/bpf_trace.c:bpf_trace_run10",
        "kernel/trace/bpf_trace.c:bpf_trace_run9",
        "kernel/trace/bpf_trace.c:bpf_trace_run8",
        "kernel/trace/bpf_trace.c:bpf_trace_run7",
        "kernel/trace/bpf_trace.c:bpf_trace_run6",
        "kernel/trace/bpf_trace.c:bpf_trace_run5",
        "kernel/trace/bpf_trace.c:bpf_trace_run4",
        "kernel/trace/bpf_trace.c:bpf_trace_run3",
        "kernel/trace/bpf_trace.c:bpf_trace_run2",
        "kernel/trace/bpf_trace.c:bpf_trace_run1",
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963938,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072987,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284984,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582470563,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476454,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532253,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock",
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655882,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592366774,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "drivers/net/netkit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/netkit.c:netkit_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592474458,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592498156,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_xdp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592581959,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592615436,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594465735,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594549139,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594786899,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594798087,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594962020,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594968231,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594992655,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595180416,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595288156,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/netfilter/nf_bpf_link.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595380202,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596582919,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596617797,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596648665,
      "name": "__bpf_prog_run",
      "external": false,
      "loc": "include/linux/filter.h:632",
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
unsigned int __bpf_prog_run(void * ctx, const struct bpf_insn * insn)
```
</details>
</li>
</ul>
