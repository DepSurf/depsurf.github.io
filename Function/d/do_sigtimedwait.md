# Function: <code>do_sigtimedwait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_sigtimedwait(const sigset_t * which, siginfo_t * info, const struct timespec * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439616,
      "name": "do_sigtimedwait",
      "external": true,
      "loc": "kernel/signal.c:2749",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SYSC_rt_sigtimedwait",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439616,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int do_sigtimedwait(const sigset_t * which, siginfo_t * info, const struct timespec * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452256,
      "name": "do_sigtimedwait",
      "external": true,
      "loc": "kernel/signal.c:2753",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SYSC_rt_sigtimedwait",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452256,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int do_sigtimedwait(const sigset_t * which, siginfo_t * info, const struct timespec * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579472720,
      "name": "do_sigtimedwait",
      "external": true,
      "loc": "kernel/signal.c:2766",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SYSC_rt_sigtimedwait",
        "kernel/compat.c:C_SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472720,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int do_sigtimedwait(const sigset_t * which, siginfo_t * info, const struct timespec * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447472,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:2787",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigtimedwait",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447472,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int do_sigtimedwait(const sigset_t * which, siginfo_t * info, const struct timespec * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475856,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:2810",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigtimedwait",
        "kernel/signal.c:SYSC_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475856,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579492224,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3041",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__do_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492224,
      "name": "do_sigtimedwait.isra.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579525776,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3303",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525776,
      "name": "do_sigtimedwait.isra.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545488,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3432",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545488,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579571600,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571600,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579603120,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3455",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603120,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583328,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3475",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583328,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590512,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3497",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590512,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667968,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3585",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667968,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763584,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3567",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763584,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896352,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3569",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896352,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945760,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3593",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945760,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985152,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3604",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985152,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490734024,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490734024,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224786028,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224786028,
      "name": "do_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283557056,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__se_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__se_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283557056,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271455124,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547904,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547904,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476640,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476640,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545184,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545184,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578176,
      "name": "do_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3437",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait_time32",
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578176,
      "name": "do_sigtimedwait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int do_sigtimedwait(const sigset_t * which, siginfo_t * info, const struct timespec * ts)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int do_sigtimedwait(const sigset_t * which, kernel_siginfo_t * info, const struct timespec64 * ts)
```
</details>
</li>
</ul>
