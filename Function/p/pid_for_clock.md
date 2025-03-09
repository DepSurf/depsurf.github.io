# Function: <code>pid_for_clock</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580232521,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:50",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231440,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580216762,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:50",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215648,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580222026,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:50",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220928,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580370074,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:50",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368944,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580586658,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:57",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585248,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580848402,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:57",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846960,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580931842,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:57",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930432,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
```

```json
{
  "name": "pid_for_clock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581022466,
      "name": "pid_for_clock",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:57",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres",
        "kernel/time/posix-cpu-timers.c:process_cpu_clock_getres"
      ],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_create",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021056,
      "name": "pid_for_clock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
struct pid * pid_for_clock(const clockid_t clock, bool gettime)
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
