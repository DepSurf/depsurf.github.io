# Function: <code>membarrier_exec_mmap</code>

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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900096,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900096,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943248,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943248,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931440,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:216",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931440,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939280,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:216",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939280,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064304,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:217",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064304,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208384,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:216",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208384,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400928,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:216",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400928,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469712,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:217",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469712,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529536,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:220",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:exec_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529536,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491099112,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491099112,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225101816,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225101816,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283989344,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283989344,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271680846,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271680846,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872208,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872208,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807216,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807216,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860368,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860368,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```

```json
{
  "name": "membarrier_exec_mmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905744,
      "name": "membarrier_exec_mmap",
      "external": true,
      "loc": "kernel/sched/membarrier.c:50",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905744,
      "name": "membarrier_exec_mmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void membarrier_exec_mmap(struct mm_struct * mm)
```
</details>
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
