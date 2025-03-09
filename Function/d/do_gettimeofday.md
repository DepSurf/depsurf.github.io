# Function: <code>do_gettimeofday</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval * tv)
```

```json
{
  "name": "do_gettimeofday",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851216,
      "name": "do_gettimeofday",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1141",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/time/time.c:SyS_gettimeofday",
        "kernel/compat.c:compat_SyS_gettimeofday",
        "kernel/compat.c:compat_SyS_time",
        "fs/coredump.c:do_coredump",
        "drivers/input/misc/uinput.c:uinput_dev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851216,
      "name": "do_gettimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void do_gettimeofday(struct timeval * tv)
```

```json
{
  "name": "do_gettimeofday",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880176,
      "name": "do_gettimeofday",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1146",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_gettimeofday",
        "kernel/compat.c:compat_SyS_time",
        "kernel/compat.c:compat_SyS_gettimeofday",
        "drivers/input/misc/uinput.c:uinput_dev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880176,
      "name": "do_gettimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void do_gettimeofday(struct timeval * tv)
```

```json
{
  "name": "do_gettimeofday",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892240,
      "name": "do_gettimeofday",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1175",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_gettimeofday",
        "kernel/compat.c:compat_SyS_time",
        "kernel/compat.c:compat_SyS_gettimeofday",
        "drivers/input/misc/uinput.c:uinput_dev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892240,
      "name": "do_gettimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void do_gettimeofday(struct timeval * tv)
```

```json
{
  "name": "do_gettimeofday",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900752,
      "name": "do_gettimeofday",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1205",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_gettimeofday",
        "kernel/time/time.c:SyS_gettimeofday",
        "kernel/time/time.c:compat_SyS_time",
        "drivers/input/misc/uinput.c:uinput_dev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900752,
      "name": "do_gettimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void do_gettimeofday(struct timeval * tv)
```

```json
{
  "name": "do_gettimeofday",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945552,
      "name": "do_gettimeofday",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1209",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_gettimeofday",
        "kernel/time/time.c:SyS_gettimeofday",
        "kernel/time/time.c:compat_SyS_time",
        "drivers/input/misc/uinput.c:uinput_dev_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945552,
      "name": "do_gettimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void do_gettimeofday(struct timeval * tv)
```

```json
{
  "name": "do_gettimeofday",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993904,
      "name": "do_gettimeofday",
      "external": true,
      "loc": "kernel/time/timekeeping.c:1210",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_compat_sys_gettimeofday",
        "kernel/time/time.c:__ia32_sys_gettimeofday",
        "kernel/time/time.c:__x64_sys_gettimeofday",
        "kernel/time/time.c:__x32_compat_sys_time",
        "kernel/time/time.c:__ia32_compat_sys_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993904,
      "name": "do_gettimeofday",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void do_gettimeofday(struct timeval * tv)
```
</details>
</li>
</ul>
