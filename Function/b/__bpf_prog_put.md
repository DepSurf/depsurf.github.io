# Function: <code>__bpf_prog_put</code>

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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580490384,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:776",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490384,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580543488,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:937",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:sockmap_get_from_fd",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543488,
      "name": "__bpf_prog_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580629728,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1036",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629728,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580688288,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1219",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688288,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580755728,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1325",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755728,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580812736,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812736,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941632,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1737",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941632,
      "name": "__bpf_prog_put.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938336,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1711",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938336,
      "name": "__bpf_prog_put.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941040,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1714",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941040,
      "name": "__bpf_prog_put.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581144976,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1796",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144976,
      "name": "__bpf_prog_put.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581420048,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2040",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420048,
      "name": "__bpf_prog_put.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void __bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755280,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2066",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755280,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void __bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915808,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2145",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915808,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void __bpf_prog_put(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041680,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2185",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_link_release",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041680,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492139248,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492139248,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226031944,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226031944,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285340832,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285340832,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272305362,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272299450,
      "name": "__bpf_prog_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580781536,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781536,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580727712,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727712,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580772784,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772784,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```

```json
{
  "name": "__bpf_prog_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580831008,
      "name": "__bpf_prog_put",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_release",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831008,
      "name": "__bpf_prog_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void __bpf_prog_put(struct bpf_prog * prog)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bpf_prog_put(struct bpf_prog * prog, bool do_idr_lock)
```
</details>
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
