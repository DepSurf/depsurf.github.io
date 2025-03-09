# Function: <code>__sched_group_set_shares</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "__sched_group_set_shares",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579923190,
      "name": "__sched_group_set_shares",
      "external": false,
      "loc": "kernel/sched/fair.c:11602",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_shares"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923104,
      "name": "__sched_group_set_shares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071592109122,
      "name": "__sched_group_set_shares.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "__sched_group_set_shares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_group_set_shares",
      "external": false,
      "loc": "kernel/sched/fair.c:11720",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_shares"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042448,
      "name": "__sched_group_set_shares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071593876762,
      "name": "__sched_group_set_shares.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "__sched_group_set_shares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_group_set_shares",
      "external": false,
      "loc": "kernel/sched/fair.c:12236",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_shares"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206256,
      "name": "__sched_group_set_shares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071595978640,
      "name": "__sched_group_set_shares.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
int __sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "__sched_group_set_shares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_group_set_shares",
      "external": false,
      "loc": "kernel/sched/fair.c:12554",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_shares"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264256,
      "name": "__sched_group_set_shares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071596496559,
      "name": "__sched_group_set_shares.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __sched_group_set_shares(struct task_group * tg, long unsigned int shares)
```

```json
{
  "name": "__sched_group_set_shares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sched_group_set_shares",
      "external": false,
      "loc": "kernel/sched/fair.c:12977",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_idle",
        "kernel/sched/fair.c:sched_group_set_shares"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580337616,
      "name": "__sched_group_set_shares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
    },
    {
      "addr": 18446744071597393677,
      "name": "__sched_group_set_shares.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __sched_group_set_shares(struct task_group * tg, long unsigned int shares)
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
