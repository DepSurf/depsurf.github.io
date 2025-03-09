# Function: <code>__copy_siginfo_from_user32</code>

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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541984,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3273",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541984,
      "name": "__copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562608,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3402",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562608,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588752,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588752,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614272,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3425",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614272,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579594496,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3445",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594496,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600128,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3467",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600128,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675120,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3555",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675120,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771712,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3537",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771712,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579903728,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3539",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903728,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953456,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3563",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953456,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992752,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3574",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992752,
      "name": "__copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490752472,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__arm64_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490752472,
      "name": "__copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283578496,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__se_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283578496,
      "name": "__copy_siginfo_from_user32",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565056,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565056,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493664,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493664,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562336,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562336,
      "name": "__copy_siginfo_from_user32",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
```

```json
{
  "name": "__copy_siginfo_from_user32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595824,
      "name": "__copy_siginfo_from_user32",
      "external": false,
      "loc": "kernel/signal.c:3407",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595824,
      "name": "__copy_siginfo_from_user32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
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
int __copy_siginfo_from_user32(int signo, struct kernel_siginfo * to, const struct compat_siginfo * ufrom)
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
