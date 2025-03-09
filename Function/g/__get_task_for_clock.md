# Function: <code>__get_task_for_clock</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168496,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168496,
      "name": "__get_task_for_clock",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491389432,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491389432,
      "name": "__get_task_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225387404,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225387404,
      "name": "__get_task_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284331568,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284331568,
      "name": "__get_task_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271872616,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:do_cpu_nanosleep",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271872616,
      "name": "__get_task_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137696,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137696,
      "name": "__get_task_for_clock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082848,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082848,
      "name": "__get_task_for_clock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128768,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128768,
      "name": "__get_task_for_clock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```

```json
{
  "name": "__get_task_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180640,
      "name": "__get_task_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:88",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:process_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_getres"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180640,
      "name": "__get_task_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct task_struct * __get_task_for_clock(const clockid_t clock, bool getref, bool gettime)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
