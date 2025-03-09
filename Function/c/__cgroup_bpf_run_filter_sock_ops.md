# Function: <code>__cgroup_bpf_run_filter_sock_ops</code>

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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545536,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:256",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545536,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623344,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:513",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623344,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580751744,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:611",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580751744,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816160,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:668",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816160,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906896,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:741",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906896,
      "name": "__cgroup_bpf_run_filter_sock_ops",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960048,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960048,
      "name": "__cgroup_bpf_run_filter_sock_ops",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123168,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1088",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_ecn_create_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123168,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156960,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1112",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_ecn_create_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_output.c:tcp_ecn_send_syn",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156960,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176016,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1116",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176016,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413888,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1146",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413888,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740192,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1295",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740192,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151376,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1509",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151376,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349200,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1509",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/af_inet.c:inet_listen",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349200,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum cgroup_bpf_attach_type atype)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582515520,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1524",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rtt_estimator",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_send_synack",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/af_inet.c:__inet_listen_sk",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_synack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515520,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492309048,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492309048,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226191072,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226191072,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285548016,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285548016,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272435378,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272435378,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928848,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928848,
      "name": "__cgroup_bpf_run_filter_sock_ops",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580874912,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874912,
      "name": "__cgroup_bpf_run_filter_sock_ops",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920096,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920096,
      "name": "__cgroup_bpf_run_filter_sock_ops",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
```

```json
{
  "name": "__cgroup_bpf_run_filter_sock_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981056,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_state",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/af_inet.c:inet_listen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981056,
      "name": "__cgroup_bpf_run_filter_sock_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int __cgroup_bpf_run_filter_sock_ops(struct sock * sk, struct bpf_sock_ops_kern * sock_ops, enum bpf_attach_type type)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
