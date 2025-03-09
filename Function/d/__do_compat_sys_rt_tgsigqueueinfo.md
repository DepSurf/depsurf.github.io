# Function: <code>__do_compat_sys_rt_tgsigqueueinfo</code>

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
long int __do_compat_sys_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo * uinfo)
```

```json
{
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509120,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3334",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509120,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542517,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3658",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563141,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3906",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579589285,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579619029,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3932",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579599157,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3953",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579604665,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3975",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579679945,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4063",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579774414,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4046",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579906718,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4048",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956446,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4072",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995742,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4083",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283578908,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579565589,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494197,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579562869,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
  "name": "__do_compat_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579596357,
      "name": "__do_compat_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3914",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo"
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
long int __do_compat_sys_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo * uinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo * uinfo)
```
</details>
</li>
</ul>
