# Function: <code>get_old_itimerval32</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int get_old_itimerval32(struct itimerspec64 * o, const struct old_itimerval32 * i)
```

```json
{
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239840,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:363",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239840,
      "name": "get_old_itimerval32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int get_old_itimerval32(struct itimerspec64 * o, const struct old_itimerval32 * i)
```

```json
{
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224048,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224048,
      "name": "get_old_itimerval32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int get_old_itimerval32(struct itimerspec64 * o, const struct old_itimerval32 * i)
```

```json
{
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229216,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229216,
      "name": "get_old_itimerval32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int get_old_itimerval32(struct itimerspec64 * o, const struct old_itimerval32 * i)
```

```json
{
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580377984,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x64_compat_sys_setitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580377984,
      "name": "get_old_itimerval32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580598529,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
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
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580861425,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
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
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580945185,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
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
  "name": "get_old_itimerval32",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581036481,
      "name": "get_old_itimerval32",
      "external": false,
      "loc": "kernel/time/itimer.c:359",
      "file": "kernel/time/itimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/itimer.c:__ia32_compat_sys_setitimer"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int get_old_itimerval32(struct itimerspec64 * o, const struct old_itimerval32 * i)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int get_old_itimerval32(struct itimerspec64 * o, const struct old_itimerval32 * i)
```
</details>
</li>
</ul>
