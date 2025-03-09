# Function: <code>__do_compat_sys_rt_sigaction</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579511443,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:3675",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547251,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4002",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568995,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4250",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595059,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579627923,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4276",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction * act, struct compat_sigaction * oact, compat_size_t sigsetsize)
```

```json
{
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606944,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4313",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606944,
      "name": "__do_compat_sys_rt_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction * act, struct compat_sigaction * oact, compat_size_t sigsetsize)
```

```json
{
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613072,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4335",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613072,
      "name": "__do_compat_sys_rt_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579690435,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4419",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x64_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579787939,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4434",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579922115,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4436",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972099,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4460",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011507,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4471",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction * act, struct compat_sigaction * oact, compat_size_t sigsetsize)
```

```json
{
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490757440,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490757440,
      "name": "__do_compat_sys_rt_sigaction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283583300,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579571363,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499971,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568643,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
  "name": "__do_compat_sys_rt_sigaction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579602131,
      "name": "__do_compat_sys_rt_sigaction",
      "external": false,
      "loc": "kernel/signal.c:4258",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__x32_compat_sys_rt_sigaction",
        "kernel/signal.c:__ia32_compat_sys_rt_sigaction"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction * act, struct compat_sigaction * oact, compat_size_t sigsetsize)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction * act, struct compat_sigaction * oact, compat_size_t sigsetsize)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction * act, struct compat_sigaction * oact, compat_size_t sigsetsize)
```
</details>
</li>
</ul>
