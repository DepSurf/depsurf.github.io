# Function: <code>sock_gen_cookie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586393872,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "net/core/sock_diag.c:22",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_diag.c:sock_diag_check_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393872,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586834736,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "net/core/sock_diag.c:22",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586834736,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025664,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "net/core/sock_diag.c:22",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025664,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587155440,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:22",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155440,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587663840,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:22",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587663840,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991136,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:23",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_getsockopt",
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
      "addr": 18446744071587991136,
      "name": "sock_gen_cookie",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588149936,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:23",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071588149936,
      "name": "sock_gen_cookie",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588471040,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071588471040,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588676496,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071588676496,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589542128,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
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
      "addr": 18446744071589542128,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589230451,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589551413,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589626164,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
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
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589122436,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589402954,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_get_socket_ptr_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589449365,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589515407,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589798909,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
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
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589841523,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590129242,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_get_socket_ptr_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590184725,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590258293,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590559065,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
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
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591375473,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591680796,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_get_socket_ptr_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591747525,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591846461,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592174358,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
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
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593134147,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593466460,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_get_socket_ptr_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593537493,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593643930,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594002411,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
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
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593585847,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593933292,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_get_socket_ptr_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594005877,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594121370,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594378689,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
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
  "name": "sock_gen_cookie",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594358672,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594716108,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_get_socket_ptr_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594790437,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie",
        "net/core/sock_diag.c:sock_diag_check_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594916954,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/core/net-traces.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595179809,
      "name": "sock_gen_cookie",
      "external": false,
      "loc": "include/linux/sock_diag.h:30",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502230032,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446603336502230032,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234975600,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 3234975600,
      "name": "sock_gen_cookie",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295718928,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 13835058055295718928,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278471996,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_diag_save_cookie"
      ],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
        "net/core/filter.c:bpf_get_socket_cookie_sock_addr",
        "net/core/filter.c:bpf_get_socket_cookie",
        "net/core/net-traces.c:perf_trace_tcp_probe",
        "net/core/net-traces.c:perf_trace_tcp_event_sk",
        "net/core/net-traces.c:trace_event_raw_event_tcp_probe",
        "net/core/net-traces.c:trace_event_raw_event_tcp_event_sk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278473850,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588283232,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071588283232,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996048,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071587996048,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588615056,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071588615056,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
u64 sock_gen_cookie(struct sock * sk)
```

```json
{
  "name": "sock_gen_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588752768,
      "name": "sock_gen_cookie",
      "external": true,
      "loc": "net/core/sock_diag.c:24",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_lookup_elem",
        "net/core/sock.c:sock_getsockopt",
        "net/core/filter.c:bpf_get_socket_cookie_sock_ops",
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
      "addr": 18446744071588752768,
      "name": "sock_gen_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
u64 sock_gen_cookie(struct sock * sk)
```
</details>
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
