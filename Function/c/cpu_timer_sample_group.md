# Function: <code>cpu_timer_sample_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, long long unsigned int * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839680,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:562",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839680,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, long long unsigned int * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868624,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:565",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868624,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, long long unsigned int * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924320,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:561",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924320,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933424,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:544",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933424,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978960,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:545",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978960,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030064,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:546",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030064,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076944,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:546",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076944,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_timer_sample_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120416,
      "name": "cpu_timer_sample_group",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:546",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:set_process_cpu_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120416,
      "name": "cpu_timer_sample_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long long unsigned int * sample</code> ➡️ <code>u64 * sample</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int cpu_timer_sample_group(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```
</details>
</li>
</ul>
