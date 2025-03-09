# Function: <code>__oom_reap_task_mm</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool __oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633984,
      "name": "__oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:464",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633984,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
bool __oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580665216,
      "name": "__oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:469",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665216,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
bool __oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750208,
      "name": "__oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:488",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750208,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
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
void __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888448,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:482",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888448,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962176,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:503",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962176,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059184,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059184,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114944,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114944,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298704,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:513",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reap_task_mm",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298704,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342704,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:515",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reap_task_mm",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342704,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361856,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:514",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361856,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609104,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:515",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609104,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969072,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969072,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395360,
      "name": "__oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395360,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601216,
      "name": "__oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601216,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772672,
      "name": "__oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:509",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772672,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492483120,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492483120,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226356156,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226356156,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285768880,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285768880,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272547908,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272547908,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083792,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083792,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030976,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030976,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074992,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074992,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool __oom_reap_task_mm(struct mm_struct * mm)
```

```json
{
  "name": "__oom_reap_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136736,
      "name": "__oom_reap_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:512",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_reaper",
        "mm/mmap.c:exit_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136736,
      "name": "__oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool __oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm</code> ➡️ <code>mm</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
