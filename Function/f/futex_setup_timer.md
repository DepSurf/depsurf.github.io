# Function: <code>futex_setup_timer</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580162250,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:484",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211525,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580274437,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:418",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580258543,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:400",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580267327,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:399",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580417633,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:457",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hrtimer_sleeper * futex_setup_timer(ktime_t * time, struct hrtimer_sleeper * timeout, int flags, u64 range_ns)
```

```json
{
  "name": "futex_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624160,
      "name": "futex_setup_timer",
      "external": true,
      "loc": "kernel/futex/core.c:135",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624160,
      "name": "futex_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct hrtimer_sleeper * futex_setup_timer(ktime_t * time, struct hrtimer_sleeper * timeout, int flags, u64 range_ns)
```

```json
{
  "name": "futex_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890032,
      "name": "futex_setup_timer",
      "external": true,
      "loc": "kernel/futex/core.c:135",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890032,
      "name": "futex_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct hrtimer_sleeper * futex_setup_timer(ktime_t * time, struct hrtimer_sleeper * timeout, int flags, u64 range_ns)
```

```json
{
  "name": "futex_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973872,
      "name": "futex_setup_timer",
      "external": true,
      "loc": "kernel/futex/core.c:135",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:__do_sys_futex_waitv",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973872,
      "name": "futex_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct hrtimer_sleeper * futex_setup_timer(ktime_t * time, struct hrtimer_sleeper * timeout, int flags, u64 range_ns)
```

```json
{
  "name": "futex_setup_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068608,
      "name": "futex_setup_timer",
      "external": true,
      "loc": "kernel/futex/core.c:136",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:futex2_setup_timeout",
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/waitwake.c:futex_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068608,
      "name": "futex_setup_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491442204,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225435272,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284398432,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271907622,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580180325,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127861,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580171797,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
  "name": "futex_setup_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580221093,
      "name": "futex_setup_timer",
      "external": false,
      "loc": "kernel/futex.c:489",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct hrtimer_sleeper * futex_setup_timer(ktime_t * time, struct hrtimer_sleeper * timeout, int flags, u64 range_ns)
```
</details>
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
