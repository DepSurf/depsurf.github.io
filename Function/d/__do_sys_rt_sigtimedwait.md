# Function: <code>__do_sys_rt_sigtimedwait</code>

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
long int __do_sys_rt_sigtimedwait(const sigset_t * uthese, siginfo_t * uinfo, const struct timespec * uts, size_t sigsetsize)
```

```json
{
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507408,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3099",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507408,
      "name": "__do_sys_rt_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542701,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3361",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563328,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3490",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579589472,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579604064,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3513",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579584272,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3533",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579591456,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3555",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668912,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3643",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579764185,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3626",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579917815,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3628",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579967703,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3652",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580007111,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3663",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224802120,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283579300,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
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
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271455078,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579565776,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494384,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563056,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
  "name": "__do_sys_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579596544,
      "name": "__do_sys_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:3495",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigtimedwait",
        "kernel/signal.c:__x64_sys_rt_sigtimedwait"
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
long int __do_sys_rt_sigtimedwait(const sigset_t * uthese, siginfo_t * uinfo, const struct timespec * uts, size_t sigsetsize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long int __do_sys_rt_sigtimedwait(const sigset_t * uthese, siginfo_t * uinfo, const struct timespec * uts, size_t sigsetsize)
```
</details>
</li>
</ul>
