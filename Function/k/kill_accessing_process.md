# Function: <code>kill_accessing_process</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int kill_accessing_process(struct task_struct * p, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_accessing_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592226556,
      "name": "kill_accessing_process",
      "external": false,
      "loc": "mm/memory-failure.c:694",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592226556,
      "name": "kill_accessing_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int kill_accessing_process(struct task_struct * p, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_accessing_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594005504,
      "name": "kill_accessing_process",
      "external": false,
      "loc": "mm/memory-failure.c:691",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594005504,
      "name": "kill_accessing_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int kill_accessing_process(struct task_struct * p, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_accessing_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427408,
      "name": "kill_accessing_process",
      "external": false,
      "loc": "mm/memory-failure.c:753",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427408,
      "name": "kill_accessing_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int kill_accessing_process(struct task_struct * p, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_accessing_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583648160,
      "name": "kill_accessing_process",
      "external": false,
      "loc": "mm/memory-failure.c:850",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583648160,
      "name": "kill_accessing_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int kill_accessing_process(struct task_struct * p, long unsigned int pfn, int flags)
```

```json
{
  "name": "kill_accessing_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842992,
      "name": "kill_accessing_process",
      "external": false,
      "loc": "mm/memory-failure.c:852",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842992,
      "name": "kill_accessing_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int kill_accessing_process(struct task_struct * p, long unsigned int pfn, int flags)
```
</details>
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
