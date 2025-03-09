# Function: <code>__do_sys_perf_event_open</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802800,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10398",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802800,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3815
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869376,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10441",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869376,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3842
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580966208,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10788",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966208,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020368,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020368,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200864,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:11484",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200864,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3805
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242848,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:11768",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242848,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4131
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259680,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:11935",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259680,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4035
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500656,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:12079",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500656,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4048
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581849248,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:12035",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849248,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3838
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276128,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:12301",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582276128,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3337
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477008,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:12341",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477008,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3418
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645600,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:12425",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645600,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3489
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492373128,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__arm64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492373128,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2668
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226258436,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__se_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226258436,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2820
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285628736,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__se_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285628736,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3600
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272479800,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__se_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272479800,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2256
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989216,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989216,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3527
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935408,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935408,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3527
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980416,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980416,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3527
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
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```

```json
{
  "name": "__do_sys_perf_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041248,
      "name": "__do_sys_perf_event_open",
      "external": false,
      "loc": "kernel/events/core.c:10889",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__ia32_sys_perf_event_open",
        "kernel/events/core.c:__x64_sys_perf_event_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041248,
      "name": "__do_sys_perf_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3573
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __do_sys_perf_event_open(struct perf_event_attr * attr_uptr, pid_t pid, int cpu, int group_fd, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
