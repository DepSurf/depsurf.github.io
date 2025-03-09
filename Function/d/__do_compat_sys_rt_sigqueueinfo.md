# Function: <code>__do_compat_sys_rt_sigqueueinfo</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo * uinfo)
```

```json
{
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508944,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3291",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508944,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542399,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3618",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563023,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3866",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579589167,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579620047,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3892",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579600463,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3913",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605968,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3935",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579681248,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4023",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x64_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579775592,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4006",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579908008,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4008",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579957736,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4032",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579997016,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4043",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283578732,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579565471,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494079,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579562751,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
  "name": "__do_compat_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579596239,
      "name": "__do_compat_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3874",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo * uinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo * uinfo)
```
</details>
</li>
</ul>
