# Function: <code>bpf_struct_ops_get</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139248,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:628",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_ca_dst_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139248,
      "name": "bpf_struct_ops_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173216,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:616",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_ca_dst_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173216,
      "name": "bpf_struct_ops_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581191632,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:616",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581191632,
      "name": "bpf_struct_ops_get",
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
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431888,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:620",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431888,
      "name": "bpf_struct_ops_get",
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
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758704,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:659",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_ipv4.c:tcp_sk_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758704,
      "name": "bpf_struct_ops_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582174912,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:660",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_ipv4.c:tcp_sk_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174912,
      "name": "bpf_struct_ops_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582372624,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:733",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_ipv4.c:tcp_sk_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372624,
      "name": "bpf_struct_ops_get",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool bpf_struct_ops_get(const void * kdata)
```

```json
{
  "name": "bpf_struct_ops_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539872,
      "name": "bpf_struct_ops_get",
      "external": true,
      "loc": "kernel/bpf/bpf_struct_ops.c:757",
      "file": "kernel/bpf/bpf_struct_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_ipv4.c:tcp_sk_init",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_ca_openreq_child",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control",
        "net/ipv4/tcp_cong.c:tcp_assign_congestion_control",
        "net/mptcp/sched.c:mptcp_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539872,
      "name": "bpf_struct_ops_get",
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
bool bpf_struct_ops_get(const void * kdata)
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
