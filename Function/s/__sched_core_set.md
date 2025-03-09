# Function: <code>__sched_core_set</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sched_core_set(struct task_struct * p, long unsigned int cookie)
```

```json
{
  "name": "__sched_core_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580075924,
      "name": "__sched_core_set",
      "external": false,
      "loc": "kernel/sched/core_sched.c:118",
      "file": "kernel/sched/core_sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core_sched.c:sched_core_share_pid"
      ],
      "caller_func": [
        "kernel/sched/core_sched.c:sched_core_share_pid",
        "kernel/sched/core_sched.c:sched_core_share_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074608,
      "name": "__sched_core_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void __sched_core_set(struct task_struct * p, long unsigned int cookie)
```

```json
{
  "name": "__sched_core_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_core_set",
      "external": false,
      "loc": "kernel/sched/core_sched.c:120",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174704,
      "name": "__sched_core_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    },
    {
      "addr": 18446744071593885444,
      "name": "__sched_core_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __sched_core_set(struct task_struct * p, long unsigned int cookie)
```

```json
{
  "name": "__sched_core_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_core_set",
      "external": false,
      "loc": "kernel/sched/core_sched.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355744,
      "name": "__sched_core_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071595982602,
      "name": "__sched_core_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __sched_core_set(struct task_struct * p, long unsigned int cookie)
```

```json
{
  "name": "__sched_core_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_core_set",
      "external": false,
      "loc": "kernel/sched/core_sched.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422000,
      "name": "__sched_core_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071596500633,
      "name": "__sched_core_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __sched_core_set(struct task_struct * p, long unsigned int cookie)
```

```json
{
  "name": "__sched_core_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_core_set",
      "external": false,
      "loc": "kernel/sched/core_sched.c:121",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480224,
      "name": "__sched_core_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
    },
    {
      "addr": 18446744071597398203,
      "name": "__sched_core_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __sched_core_set(struct task_struct * p, long unsigned int cookie)
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
