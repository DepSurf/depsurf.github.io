# Function: <code>bpf_dispatcher_nop_func</code>

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
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580571062,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580846910,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032605,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134185,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143453,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817302,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587836977,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589311706,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589540252,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589546530,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589579997,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589639438,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589643778,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589847997,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590901650,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590950992,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:550",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580563743,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580835646,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040668,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168330,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183410,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877051,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587895073,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589310680,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589549404,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589555554,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589590652,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589663150,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589667458,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885936,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590040374,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590243046,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590797952,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590963010,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590982752,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591013573,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:660",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580566849,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841502,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054057,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186824,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201794,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587756267,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587773873,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204733,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589447356,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589453565,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/sock_reuseport.c:run_bpf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589554718,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589559712,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589651981,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589799072,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589954582,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590157014,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590724608,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590899965,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590913424,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590946509,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:678",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580736910,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041307,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279035,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426720,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441164,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588350580,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588369451,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589926714,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590182447,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:sk_filter_trim_cap",
        "net/core/filter.c:sk_filter_trim_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590189450,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:run_bpf_filter",
        "net/core/sock_reuseport.c:run_bpf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590299499,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590304688,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590409034,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559552,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590721747,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590937427,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591539581,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591733581,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:input_action_end_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591749181,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591782365,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:711",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
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
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580949678,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_run_filters",
        "kernel/seccomp.c:seccomp_run_filters"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299964,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432202,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573234,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752946,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782054,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589726283,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589767904,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591459022,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591744981,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591752297,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591883147,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591888665,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592000999,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592174965,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592350743,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592580343,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593229060,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593426697,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593455412,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593483107,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:863",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int bpf_dispatcher_nop_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
```

```json
{
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581245418,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626076,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695897,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785370,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949837,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107808,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/bpf/dispatcher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582168050,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284242,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591349770,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591418147,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593227097,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593534693,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593542649,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593684811,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593690889,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593821004,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594003029,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594189831,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594442359,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595129188,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595340169,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595372484,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595401443,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1084",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107808,
      "name": "bpf_dispatcher_nop_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593438144,
      "name": "bpf_dispatcher_nop_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
unsigned int bpf_dispatcher_nop_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
```

```json
{
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581340377,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763527,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840840,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946534,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137645,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303648,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/bpf/dispatcher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582365202,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582487164,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591711493,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591833900,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593687577,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594002581,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594011721,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594165468,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594171689,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594195729,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594379301,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594485934,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/netfilter/nf_bpf_link.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf",
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594576934,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594832566,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595523569,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595735113,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595769649,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595797990,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1162",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303648,
      "name": "bpf_dispatcher_nop_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593903040,
      "name": "bpf_dispatcher_nop_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
unsigned int bpf_dispatcher_nop_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
```

```json
{
  "name": "bpf_dispatcher_nop_func",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581447385,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882279,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/trace/bpf_trace.c:trace_call_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963943,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func",
        "kernel/trace/trace_uprobe.c:__uprobe_perf_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072989,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284989,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog",
        "kernel/bpf/bpf_iter.c:bpf_iter_run_prog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464720,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/bpf/dispatcher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582532258,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "kernel/bpf/cgroup.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655884,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:bpf_overflow_handler",
        "kernel/events/core.c:bpf_overflow_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592366779,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "drivers/net/netkit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/netkit.c:netkit_xmit",
        "drivers/net/netkit.c:netkit_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592455223,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_select_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592581964,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_send_frame"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594465737,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/flow_dissector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:bpf_flow_dissect",
        "net/core/flow_dissector.c:bpf_flow_dissect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594547946,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594786901,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:bpf_run_sk_reuseport",
        "net/core/filter.c:__bpf_prog_run_save_cb",
        "net/core/filter.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594798089,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/sock_reuseport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb",
        "net/core/sock_reuseport.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594962028,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/ptp_classifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_classify_raw",
        "net/core/ptp_classifier.c:ptp_classify_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594968233,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/lwt_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb",
        "net/core/lwt_bpf.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594992657,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read",
        "net/core/skmsg.c:sk_psock_msg_verdict",
        "net/core/skmsg.c:sk_psock_msg_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595180421,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:__bpf_prog_test_run_raw_tp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595288158,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/netfilter/nf_bpf_link.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf",
        "net/netfilter/nf_bpf_link.c:nf_hook_run_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595380207,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4",
        "net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596582921,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb",
        "net/ipv6/seg6_local.c:__bpf_prog_run_save_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596617802,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6",
        "net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596648674,
      "name": "bpf_dispatcher_nop_func",
      "external": false,
      "loc": "include/linux/bpf.h:1226",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464720,
      "name": "bpf_dispatcher_nop_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594686384,
      "name": "bpf_dispatcher_nop_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
unsigned int bpf_dispatcher_nop_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
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
