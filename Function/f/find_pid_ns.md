# Function: <code>find_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490976,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:366",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/pid.c:find_ge_pid",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490976,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504896,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:366",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:find_ge_pid",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504896,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525568,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:366",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:find_ge_pid",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525568,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513248,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:367",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:find_ge_pid",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513248,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579541024,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:244",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540880,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568702,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:256",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568544,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605774,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:258",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605632,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629690,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629552,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579655242,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655104,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686433,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:308",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685984,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664877,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:309",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664112,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671821,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:309",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670928,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749373,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:309",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748592,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858288,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:309",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852976,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999472,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:309",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993664,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048897,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:312",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "kernel/bpf/task_iter.c:task_group_seq_get_next",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047488,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091393,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:312",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089984,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490828384,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490828208,
      "name": "find_pid_ns",
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224861772,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_task_by_vpid",
        "kernel/pid.c:find_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859832,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283662644,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283662416,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271500456,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271500298,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631562,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631424,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579559898,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559760,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628826,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628688,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
struct pid * find_pid_ns(int nr, struct pid_namespace * ns)
```

```json
{
  "name": "find_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662372,
      "name": "find_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:261",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662112,
      "name": "find_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
