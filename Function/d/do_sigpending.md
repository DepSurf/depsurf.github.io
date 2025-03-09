# Function: <code>do_sigpending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579438561,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2604",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:compat_SyS_rt_sigpending",
        "kernel/signal.c:SyS_sigpending"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579455084,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2604",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SyS_sigpending",
        "kernel/signal.c:compat_SyS_rt_sigpending"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579475564,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2617",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:SyS_sigpending",
        "kernel/signal.c:compat_SyS_rt_sigpending"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579463628,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2638",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:compat_SyS_sigpending",
        "kernel/signal.c:SyS_sigpending",
        "kernel/signal.c:compat_SyS_rt_sigpending"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473680,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2625",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_sigpending",
        "kernel/signal.c:SyS_sigpending",
        "kernel/signal.c:compat_SyS_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473680,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488080,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2758",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488080,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521632,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:2936",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521632,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541296,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3065",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541296,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567376,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567376,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600736,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3088",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600736,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580944,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3108",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580944,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586496,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3130",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586496,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661728,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3215",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x64_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661728,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751136,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3195",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751136,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883072,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3197",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883072,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932336,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932336,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971664,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3232",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971664,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490726784,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_sigpending",
        "kernel/signal.c:__arm64_sys_sigpending",
        "kernel/signal.c:__arm64_compat_sys_rt_sigpending",
        "kernel/signal.c:__arm64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490726784,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224778240,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_sigpending",
        "kernel/signal.c:__se_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224778240,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283551440,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_sigpending",
        "kernel/signal.c:__se_sys_sigpending",
        "kernel/signal.c:__se_compat_sys_rt_sigpending",
        "kernel/signal.c:__se_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283551440,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271446882,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigpending"
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543680,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543680,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579472432,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472432,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540960,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540960,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void do_sigpending(sigset_t * set)
```

```json
{
  "name": "do_sigpending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569872,
      "name": "do_sigpending",
      "external": false,
      "loc": "kernel/signal.c:3070",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_compat_sys_sigpending",
        "kernel/signal.c:__ia32_sys_sigpending",
        "kernel/signal.c:__x64_sys_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_sys_rt_sigpending",
        "kernel/signal.c:__x64_sys_rt_sigpending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569872,
      "name": "do_sigpending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int do_sigpending(sigset_t * set)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_sigpending(sigset_t * set)
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
