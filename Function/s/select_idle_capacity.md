# Function: <code>select_idle_capacity</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```

```json
{
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803904,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:6160",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803904,
      "name": "select_idle_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```

```json
{
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795552,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:6211",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795552,
      "name": "select_idle_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579812331,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:6293",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_sibling"
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
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579912375,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:6361",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_sibling"
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
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032285,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:6430",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_sibling"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```

```json
{
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177728,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:6801",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177728,
      "name": "select_idle_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```

```json
{
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246736,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:7054",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246736,
      "name": "select_idle_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
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
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```

```json
{
  "name": "select_idle_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298400,
      "name": "select_idle_capacity",
      "external": false,
      "loc": "kernel/sched/fair.c:7426",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:select_idle_sibling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298400,
      "name": "select_idle_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
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
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
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
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int select_idle_capacity(struct task_struct * p, struct sched_domain * sd, int target)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
