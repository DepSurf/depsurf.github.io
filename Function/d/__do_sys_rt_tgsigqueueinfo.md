# Function: <code>__do_sys_rt_tgsigqueueinfo</code>

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
long int __do_sys_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t * uinfo)
```

```json
{
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498368,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3322",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498368,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579531828,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3647",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558388,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3895",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584516,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618580,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3921",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579598900,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3942",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579604405,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3964",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579679685,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4052",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579774235,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4035",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579906523,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4037",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956251,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4061",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995547,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4072",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_sys_rt_tgsigqueueinfo"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224804052,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283573084,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271456698,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579560820,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579489476,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558100,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
  "name": "__do_sys_rt_tgsigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579591492,
      "name": "__do_sys_rt_tgsigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3903",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_tgsigqueueinfo"
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
long int __do_sys_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t * uinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long int __do_sys_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t * uinfo)
```
</details>
</li>
</ul>
