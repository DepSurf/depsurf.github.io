# Function: <code>dup_task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363181,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:339",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579370467,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:346",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389260,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:478",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579376665,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:509",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403483,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:517",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579419182,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:797",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579450208,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:841",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468547,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:847",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494608,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523616,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:871",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523616,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505360,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:856",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505360,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508800,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508800,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577888,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:879",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577888,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668800,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:967",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668800,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788848,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:977",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788848,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836320,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:1103",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836320,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876352,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:1102",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876352,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490627056,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490627056,
      "name": "dup_task_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224706344,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283446612,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271383890,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468272,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397194,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468192,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_task_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499927,
      "name": "dup_task_struct",
      "external": false,
      "loc": "kernel/fork.c:861",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct task_struct * dup_task_struct(struct task_struct * orig, int node)
```
</details>
</li>
</ul>
