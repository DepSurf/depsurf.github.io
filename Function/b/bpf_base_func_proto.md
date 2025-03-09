# Function: <code>bpf_base_func_proto</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587144048,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:2891",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:lwt_inout_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144048,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587649536,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:3331",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:lwt_inout_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649536,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587967712,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:4734",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967712,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588118832,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5290",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588118832,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588437936,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5890",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437936,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588644368,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644368,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028192,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:611",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cg_sockopt_func_proto",
        "kernel/bpf/cgroup.c:sysctl_func_proto",
        "kernel/bpf/cgroup.c:cgroup_dev_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_seg6local_func_proto",
        "net/core/filter.c:lwt_in_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:cg_skb_func_proto",
        "net/core/filter.c:sock_addr_func_proto",
        "net/core/filter.c:sock_filter_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028192,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035344,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:672",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cg_sockopt_func_proto",
        "kernel/bpf/cgroup.c:sysctl_func_proto",
        "kernel/bpf/cgroup.c:cgroup_dev_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sock_filter_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035344,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 850
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048784,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:999",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cg_sockopt_func_proto",
        "kernel/bpf/cgroup.c:sysctl_func_proto",
        "kernel/bpf/cgroup.c:cgroup_dev_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sock_filter_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048784,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273216,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1343",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/syscall.c:tracing_prog_func_proto",
        "kernel/bpf/cgroup.c:cg_sockopt_func_proto",
        "kernel/bpf/cgroup.c:sysctl_func_proto",
        "kernel/bpf/cgroup.c:cgroup_dev_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sock_filter_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273216,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 979
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566160,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1591",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/syscall.c:tracing_prog_func_proto",
        "kernel/bpf/cgroup.c:cg_sockopt_func_proto",
        "kernel/bpf/cgroup.c:sysctl_func_proto",
        "kernel/bpf/cgroup.c:cgroup_dev_func_proto",
        "net/core/filter.c:bpf_sk_base_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:sock_filter_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566160,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1399
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939472,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1585",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/syscall.c:tracing_prog_func_proto",
        "net/core/filter.c:bpf_sk_base_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939472,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1499
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123472,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1666",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/syscall.c:tracing_prog_func_proto",
        "net/core/filter.c:bpf_sk_base_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/netfilter/nf_bpf_link.c:bpf_nf_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123472,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264016,
      "name": "bpf_base_func_proto",
      "external": true,
      "loc": "kernel/bpf/helpers.c:1685",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_tracing_func_proto",
        "kernel/bpf/syscall.c:tracing_prog_func_proto",
        "net/core/filter.c:bpf_sk_base_func_proto",
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/netfilter/nf_bpf_link.c:bpf_nf_func_proto",
        "net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264016,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502188056,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502188056,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234934976,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234934976,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295668448,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295668448,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278443720,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278443720,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588251104,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588251104,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587963920,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963920,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588582928,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588582928,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "bpf_base_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588720416,
      "name": "bpf_base_func_proto",
      "external": false,
      "loc": "net/core/filter.c:5967",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_func_proto",
        "net/core/filter.c:lwt_out_func_proto",
        "net/core/filter.c:flow_dissector_func_proto",
        "net/core/filter.c:sk_skb_func_proto",
        "net/core/filter.c:sk_msg_func_proto",
        "net/core/filter.c:sock_ops_func_proto",
        "net/core/filter.c:xdp_func_proto",
        "net/core/filter.c:tc_cls_act_func_proto",
        "net/core/filter.c:sk_filter_func_proto",
        "net/core/filter.c:sock_filter_func_proto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588720416,
      "name": "bpf_base_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
const struct bpf_func_proto * bpf_base_func_proto(enum bpf_func_id func_id)
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
