# Function: <code>set_normalized_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579806848,
      "name": "set_normalized_timespec",
      "external": true,
      "loc": "kernel/time/time.c:361",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:get_monotonic_coarse64",
        "fs/select.c:poll_select_copy_remaining",
        "fs/compat.c:poll_select_copy_remaining",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806848,
      "name": "set_normalized_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579837037,
      "name": "set_normalized_timespec",
      "external": true,
      "loc": "kernel/time/time.c:368",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe",
        "kernel/time/time.c:timespec_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:get_monotonic_coarse64",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_copy_remaining",
        "fs/compat.c:poll_select_copy_remaining",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834656,
      "name": "set_normalized_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866093,
      "name": "set_normalized_timespec",
      "external": true,
      "loc": "kernel/time/time.c:368",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe",
        "kernel/time/time.c:timespec_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:get_monotonic_coarse64",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:poll_select_copy_remaining",
        "fs/compat.c:poll_select_copy_remaining",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863712,
      "name": "set_normalized_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579875581,
      "name": "set_normalized_timespec",
      "external": true,
      "loc": "kernel/time/time.c:458",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:timespec64_add_safe",
        "kernel/time/time.c:timespec_add_safe"
      ],
      "caller_func": [
        "arch/x86/kernel/pvclock.c:pvclock_read_wallclock",
        "kernel/time/timekeeping.c:get_monotonic_coarse64",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_suspend",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timekeeping.c:timekeeping_init",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "kernel/time/timekeeping.c:tk_set_wall_to_mono",
        "fs/select.c:compat_poll_select_copy_remaining",
        "fs/select.c:poll_select_copy_remaining",
        "fs/select.c:select_estimate_accuracy",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871936,
      "name": "set_normalized_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```

```json
{
  "name": "set_normalized_timespec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959904,
      "name": "set_normalized_timespec",
      "external": true,
      "loc": "kernel/time/time.c:426",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959904,
      "name": "set_normalized_timespec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void set_normalized_timespec(struct timespec * ts, time_t sec, s64 nsec)
```
</details>
</li>
</ul>
