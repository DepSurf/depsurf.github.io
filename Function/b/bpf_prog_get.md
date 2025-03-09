# Function: <code>bpf_prog_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580363200,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:586",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:perf_ioctl",
        "net/core/filter.c:sk_attach_bpf",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363200,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424064,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:707",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424064,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473456,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:804",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473456,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580494270,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:909",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493056,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550503,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1095",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548352,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580630639,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1196",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_test_run"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641104,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580699565,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1382",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702880,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768055,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1519",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772160,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580820167,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823088,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580947493,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1918",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945440,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938536,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1892",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942576,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580949587,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1900",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:perf_event_set_bpf_prog",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945056,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581153903,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1994",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149200,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581428553,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2240",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424672,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581781229,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2274",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777152,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581943897,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2353",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_get_prog_attach_type",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939312,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070681,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:2393",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/mprog.c:bpf_mprog_tuple_relative",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/events/core.c:_perf_ioctl",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "net/core/sock_map.c:sock_map_prog_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065920,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492143684,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492146288,
      "name": "bpf_prog_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226039420,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226042100,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285350768,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285354000,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272305436,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272307728,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788967,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791888,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580735143,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738064,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580780215,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580783136,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
struct bpf_prog * bpf_prog_get(u32 ufd)
```

```json
{
  "name": "bpf_prog_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580838458,
      "name": "bpf_prog_get",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1540",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_obj_pin_user",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841520,
      "name": "bpf_prog_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
