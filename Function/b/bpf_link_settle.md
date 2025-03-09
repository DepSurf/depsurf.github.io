# Function: <code>bpf_link_settle</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946563,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2447",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947168,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945011,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2463",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945360,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580947654,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2471",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948000,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581152330,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2581",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152656,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581426887,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2830",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432464,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581779511,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2864",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "net/core/dev.c:bpf_xdp_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785680,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581941719,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2983",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/netfilter/nf_bpf_link.c:bpf_nf_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946848,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_link_settle(struct bpf_link_primer * primer)
```

```json
{
  "name": "bpf_link_settle",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582068486,
      "name": "bpf_link_settle",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3047",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/tcx.c:tcx_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create",
        "drivers/net/netkit.c:netkit_link_attach",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "net/core/dev.c:bpf_xdp_link_attach",
        "net/netfilter/nf_bpf_link.c:bpf_nf_link_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073312,
      "name": "bpf_link_settle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_link_settle(struct bpf_link_primer * primer)
```
</details>
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
