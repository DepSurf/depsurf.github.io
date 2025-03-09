# Function: <code>__copy_siginfo_from_user</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520144,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3087",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520144,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538992,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3216",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538992,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565776,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565776,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597392,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3239",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597392,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577568,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3259",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577568,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583248,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3287",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583248,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657408,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3375",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657408,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579774240,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3355",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579906528,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3357",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956256,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3381",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995552,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3392",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490731064,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__arm64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490731064,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224782840,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224782840,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283549920,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283549920,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271439340,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271439340,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542080,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542080,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470144,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470144,
      "name": "__copy_siginfo_from_user",
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
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539360,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539360,
      "name": "__copy_siginfo_from_user",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```

```json
{
  "name": "__copy_siginfo_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579573040,
      "name": "__copy_siginfo_from_user",
      "external": false,
      "loc": "kernel/signal.c:3221",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573040,
      "name": "__copy_siginfo_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __copy_siginfo_from_user(int signo, kernel_siginfo_t * to, const siginfo_t * from)
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
