# Function: <code>sigsuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437856,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:3506",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigsuspend",
        "kernel/signal.c:SyS_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437856,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450288,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:3509",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_sigsuspend",
        "kernel/signal.c:compat_SyS_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450288,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470768,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:3536",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_sigsuspend",
        "kernel/signal.c:compat_SyS_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470768,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459136,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:3591",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_sigsuspend",
        "kernel/signal.c:compat_SyS_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459136,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487376,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:3606",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SyS_sigsuspend",
        "kernel/signal.c:compat_SyS_rt_sigsuspend",
        "kernel/signal.c:SyS_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487376,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505232,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:3854",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505232,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539408,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4181",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539408,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549792,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4429",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549792,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575920,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575920,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611376,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4455",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611376,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591584,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4492",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591584,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588160,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4514",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588160,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663424,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4598",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x64_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663424,
      "name": "sigsuspend",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758368,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4613",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758368,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892928,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4615",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892928,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942224,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4639",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942224,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981568,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4650",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981568,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490738840,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_sys_sigsuspend",
        "kernel/signal.c:__arm64_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__arm64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490738840,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224790380,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_sigsuspend",
        "kernel/signal.c:__se_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224790380,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283562704,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_sigsuspend",
        "kernel/signal.c:__se_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__se_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283562704,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271458010,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigsuspend"
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552224,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552224,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480928,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480928,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549504,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549504,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int sigsuspend(sigset_t * set)
```

```json
{
  "name": "sigsuspend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582640,
      "name": "sigsuspend",
      "external": false,
      "loc": "kernel/signal.c:4437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_sigsuspend",
        "kernel/signal.c:__x64_sys_sigsuspend",
        "kernel/signal.c:__x32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_compat_sys_rt_sigsuspend",
        "kernel/signal.c:__ia32_sys_rt_sigsuspend",
        "kernel/signal.c:__x64_sys_rt_sigsuspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582640,
      "name": "sigsuspend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sigsuspend(sigset_t * set)
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
