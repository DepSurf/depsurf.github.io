# Function: <code>get_itimerval</code>

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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239664,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:317",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239664,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580223872,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223872,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229040,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229040,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580377808,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580377808,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595632,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595632,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858368,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858368,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942128,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942128,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
```

```json
{
  "name": "get_itimerval",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033424,
      "name": "get_itimerval",
      "external": false,
      "loc": "kernel/time/itimer.c:313",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_sys_setitimer",
        "kernel/time/itimer.c:__x64_sys_setitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033424,
      "name": "get_itimerval",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int get_itimerval(struct itimerspec64 * o, const struct __kernel_old_itimerval * i)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
