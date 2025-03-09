# Function: <code>membarrier_update_current_mm</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931488,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:232",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931488,
      "name": "membarrier_update_current_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939328,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:232",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939328,
      "name": "membarrier_update_current_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064352,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:233",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064352,
      "name": "membarrier_update_current_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208432,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:232",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208432,
      "name": "membarrier_update_current_mm",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400992,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:232",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400992,
      "name": "membarrier_update_current_mm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469776,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:233",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469776,
      "name": "membarrier_update_current_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void membarrier_update_current_mm(struct mm_struct * next_mm)
```

```json
{
  "name": "membarrier_update_current_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529600,
      "name": "membarrier_update_current_mm",
      "external": true,
      "loc": "kernel/sched/membarrier.c:236",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529600,
      "name": "membarrier_update_current_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void membarrier_update_current_mm(struct mm_struct * next_mm)
```
</details>
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
