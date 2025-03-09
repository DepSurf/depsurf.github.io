# Function: <code>ptrace_check_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416208,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:172",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:SyS_ptrace",
        "kernel/ptrace.c:compat_SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416208,
      "name": "ptrace_check_attach",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428496,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:171",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428496,
      "name": "ptrace_check_attach",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447840,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:209",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447840,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435840,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:224",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435840,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464112,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:224",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_SyS_ptrace",
        "kernel/ptrace.c:SyS_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464112,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477616,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:224",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477616,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510960,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:224",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510960,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530544,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071579536396,
      "name": "ptrace_check_attach.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556704,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556704,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588160,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588160,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568192,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568192,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573696,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:246",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573696,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648640,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:246",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x64_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648640,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740720,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:249",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740720,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872064,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:249",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872064,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921600,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:250",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921600,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960848,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:239",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960848,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490711848,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__arm64_compat_sys_ptrace",
        "kernel/ptrace.c:__arm64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490711848,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224773660,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283535424,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_compat_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283535424,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271434480,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533008,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533008,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461776,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461776,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530288,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530288,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```

```json
{
  "name": "ptrace_check_attach",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579561456,
      "name": "ptrace_check_attach",
      "external": false,
      "loc": "kernel/ptrace.c:229",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561456,
      "name": "ptrace_check_attach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ptrace_check_attach(struct task_struct * child, bool ignore_state)
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
