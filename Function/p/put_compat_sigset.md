# Function: <code>put_compat_sigset</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int put_compat_sigset(compat_sigset_t * compat, const sigset_t * set, unsigned int size)
```

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076528,
      "name": "put_compat_sigset",
      "external": true,
      "loc": "kernel/compat.c:492",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigaction",
        "kernel/signal.c:compat_SyS_rt_sigpending",
        "kernel/signal.c:compat_SyS_rt_sigprocmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076528,
      "name": "put_compat_sigset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579511625,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:496",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547433,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:487",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579569182,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:455",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595246,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579628110,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:424",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579607170,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:424",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579613298,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:427",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579690618,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:417",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x64_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x64_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x64_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579788153,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:449",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579922329,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:447",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972358,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:447",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011766,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:447",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490757792,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_compat_sys_rt_sigaction",
        "kernel/signal.c:__arm64_compat_sys_rt_sigpending",
        "kernel/signal.c:__arm64_compat_sys_rt_sigprocmask"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282283796,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "arch/powerpc/kernel/signal_32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext",
        "arch/powerpc/kernel/signal_32.c:handle_rt_signal32"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283584060,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_compat_sys_rt_sigaction",
        "kernel/signal.c:__se_compat_sys_rt_sigpending",
        "kernel/signal.c:__se_compat_sys_rt_sigprocmask"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579571550,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500158,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568830,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_sigset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579602318,
      "name": "put_compat_sigset",
      "external": false,
      "loc": "include/linux/compat.h:453",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction",
        "kernel/signal.c:__x32_compat_sys_rt_sigpending",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/signal.c:__x32_compat_sys_rt_sigprocmask",
        "kernel/signal.c:__ia32_compat_sys_rt_sigprocmask"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int put_compat_sigset(compat_sigset_t * compat, const sigset_t * set, unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int put_compat_sigset(compat_sigset_t * compat, const sigset_t * set, unsigned int size)
```
</details>
</li>
</ul>
