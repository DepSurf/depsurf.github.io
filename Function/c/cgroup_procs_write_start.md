# Function: <code>cgroup_procs_write_start</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094000,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2628",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094000,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153088,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153088,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580200736,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2687",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200736,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247808,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2827",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247808,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296032,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296032,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580366784,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2750",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366784,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580353728,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2746",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353728,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356848,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2759",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356848,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2814",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592161060,
      "name": "cgroup_procs_write_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580514768,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2824",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593934088,
      "name": "cgroup_procs_write_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580711392,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * threadgroup_locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2920",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595999646,
      "name": "cgroup_procs_write_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580985616,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * threadgroup_locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2889",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517780,
      "name": "cgroup_procs_write_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581073136,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup, bool * threadgroup_locked)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2898",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597418002,
      "name": "cgroup_procs_write_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581170752,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491546664,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491546664,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225511072,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225511072,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284517472,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284517472,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271961888,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271961888,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264832,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264832,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212336,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212336,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256080,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256080,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```

```json
{
  "name": "cgroup_procs_write_start",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309408,
      "name": "cgroup_procs_write_start",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2828",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309408,
      "name": "cgroup_procs_write_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct task_struct * cgroup_procs_write_start(char * buf, bool threadgroup)
```
</details>
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * locked</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * threadgroup_locked</code>
</li>
<li>
<b>Param removed. </b>
<code>bool * locked</code>
</li>
</ul>
</details>
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
