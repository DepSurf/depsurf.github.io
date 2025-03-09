# Function: <code>do_sys_settimeofday</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday(const struct timespec * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579808528,
      "name": "do_sys_settimeofday",
      "external": true,
      "loc": "kernel/time/time.c:163",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set",
        "kernel/compat.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808528,
      "name": "do_sys_settimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_settimeofday",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579836748,
      "name": "do_sys_settimeofday",
      "external": false,
      "loc": "include/linux/timekeeping.h:18",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:SyS_settimeofday"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861308,
      "name": "do_sys_settimeofday",
      "external": false,
      "loc": "include/linux/timekeeping.h:18",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990654,
      "name": "do_sys_settimeofday",
      "external": false,
      "loc": "include/linux/timekeeping.h:18",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_settimeofday"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_sys_settimeofday",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579865804,
      "name": "do_sys_settimeofday",
      "external": false,
      "loc": "include/linux/timekeeping.h:18",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:SyS_settimeofday"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917388,
      "name": "do_sys_settimeofday",
      "external": false,
      "loc": "include/linux/timekeeping.h:18",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021150,
      "name": "do_sys_settimeofday",
      "external": false,
      "loc": "include/linux/timekeeping.h:18",
      "file": "kernel/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/compat.c:compat_SyS_settimeofday"
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
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int do_sys_settimeofday(const struct timespec * tv, const struct timezone * tz)
```
</details>
</li>
</ul>
