# Function: <code>__sock_gen_cookie</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589551200,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:25",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551200,
      "name": "__sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589449136,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:25",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_ptr_cookie",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449136,
      "name": "__sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590184496,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:25",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_ptr_cookie",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184496,
      "name": "__sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591747264,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:26",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_ptr_cookie",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591747264,
      "name": "__sock_gen_cookie",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593537508,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:26",
      "file": "net/core/sock_diag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sk_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_ptr_cookie",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593536800,
      "name": "__sock_gen_cookie.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071593537600,
      "name": "__sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594005892,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:26",
      "file": "net/core/sock_diag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sk_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_ptr_cookie",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594005152,
      "name": "__sock_gen_cookie.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071594005984,
      "name": "__sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u64 __sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "__sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594790452,
      "name": "__sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:26",
      "file": "net/core/sock_diag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sk_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_ptr_cookie",
        "net/core/filter.c:bpf_get_socket_cookie_sock",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594789696,
      "name": "__sock_gen_cookie.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071594790544,
      "name": "__sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
u64 __sock_gen_cookie(struct sock * sk)
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
