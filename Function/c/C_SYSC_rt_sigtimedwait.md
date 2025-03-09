# Function: <code>C_SYSC_rt_sigtimedwait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int C_SYSC_rt_sigtimedwait(compat_sigset_t * uthese, struct compat_siginfo * uinfo, struct compat_timespec * uts, compat_size_t sigsetsize)
```

```json
{
  "name": "C_SYSC_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959200,
      "name": "C_SYSC_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/compat.c:996",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959200,
      "name": "C_SYSC_rt_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
long int C_SYSC_rt_sigtimedwait(compat_sigset_t * uthese, struct compat_siginfo * uinfo, struct compat_timespec * uts, compat_size_t sigsetsize)
```

```json
{
  "name": "C_SYSC_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989872,
      "name": "C_SYSC_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/compat.c:996",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989872,
      "name": "C_SYSC_rt_sigtimedwait",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int C_SYSC_rt_sigtimedwait(compat_sigset_t * uthese, struct compat_siginfo * uinfo, struct compat_timespec * uts, compat_size_t sigsetsize)
```

```json
{
  "name": "C_SYSC_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020400,
      "name": "C_SYSC_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/compat.c:1004",
      "file": "kernel/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/compat.c:compat_SyS_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020400,
      "name": "C_SYSC_rt_sigtimedwait",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int C_SYSC_rt_sigtimedwait(compat_sigset_t * uthese, struct compat_siginfo * uinfo, struct compat_timespec * uts, compat_size_t sigsetsize)
```

```json
{
  "name": "C_SYSC_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448032,
      "name": "C_SYSC_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:2877",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448032,
      "name": "C_SYSC_rt_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
long int C_SYSC_rt_sigtimedwait(compat_sigset_t * uthese, struct compat_siginfo * uinfo, struct compat_timespec * uts, compat_size_t sigsetsize)
```

```json
{
  "name": "C_SYSC_rt_sigtimedwait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476416,
      "name": "C_SYSC_rt_sigtimedwait",
      "external": false,
      "loc": "kernel/signal.c:2900",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:compat_SyS_rt_sigtimedwait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476416,
      "name": "C_SYSC_rt_sigtimedwait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
long int C_SYSC_rt_sigtimedwait(compat_sigset_t * uthese, struct compat_siginfo * uinfo, struct compat_timespec * uts, compat_size_t sigsetsize)
```
</details>
</li>
</ul>
