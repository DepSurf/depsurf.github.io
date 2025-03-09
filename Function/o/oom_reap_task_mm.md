# Function: <code>oom_reap_task_mm</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580888869,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:522",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580962769,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:557",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581059737,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581115513,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:568",
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
      "addr": 18446744071581299120,
      "name": "oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071581301273,
      "name": "oom_reap_task_mm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
bool oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:570",
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
      "addr": 18446744071581343120,
      "name": "oom_reap_task_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    },
    {
      "addr": 18446744071591325068,
      "name": "oom_reap_task_mm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581362404,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:569",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581609652,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:570",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581969641,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582398491,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:568",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582604526,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:568",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582775982,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:565",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492483728,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226356784,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285769728,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272548382,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581084361,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581031545,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581075561,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
  "name": "oom_reap_task_mm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581137281,
      "name": "oom_reap_task_mm",
      "external": false,
      "loc": "mm/oom_kill.c:567",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
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
bool oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool oom_reap_task_mm(struct task_struct * tsk, struct mm_struct * mm)
```
</details>
</li>
</ul>
