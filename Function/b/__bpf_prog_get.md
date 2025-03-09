# Function: <code>__bpf_prog_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580363210,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:571",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_get"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * type)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580421168,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:688",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_get_type",
        "kernel/bpf/syscall.c:bpf_prog_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421168,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * type)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469616,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:785",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469616,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * type)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489920,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:890",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489920,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545264,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1075",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:sockmap_get_from_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545264,
      "name": "__bpf_prog_get",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630048,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1176",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630048,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688672,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1362",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688672,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756096,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1499",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756096,
      "name": "__bpf_prog_get",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806352,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806352,
      "name": "__bpf_prog_get",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928192,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1898",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928192,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924944,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1872",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924944,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928304,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1880",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928304,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1974",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131440,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071592180190,
      "name": "__bpf_prog_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2220",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403424,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071593954101,
      "name": "__bpf_prog_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2254",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754448,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071596013601,
      "name": "__bpf_prog_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2333",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914960,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071596533597,
      "name": "__bpf_prog_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2373",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040832,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071597434428,
      "name": "__bpf_prog_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492121968,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492121968,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226023048,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226023048,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285329712,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285329712,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272293236,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272293236,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580775152,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775152,
      "name": "__bpf_prog_get",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721328,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721328,
      "name": "__bpf_prog_get",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766400,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766400,
      "name": "__bpf_prog_get",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * attach_type, bool attach_drv)
```

```json
{
  "name": "__bpf_prog_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824560,
      "name": "__bpf_prog_get",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1520",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824560,
      "name": "__bpf_prog_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * __bpf_prog_get(u32 ufd, enum bpf_prog_type * type)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_prog_type * attach_type</code>
</li>
<li>
<b>Param added. </b>
<code>bool attach_drv</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_prog_type * type</code>
</li>
</ul>
</details>
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
