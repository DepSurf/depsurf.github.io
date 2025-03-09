# Function: <code>init_tg_rt_entry</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828780,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828192,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491014024,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491013576,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225021060,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225020584,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283888232,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283887728,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271620550,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271620248,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735532,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579734944,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```

```json
{
  "name": "init_tg_rt_entry",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789148,
      "name": "init_tg_rt_entry",
      "external": true,
      "loc": "kernel/sched/rt.c:156",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:alloc_rt_sched_group"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788560,
      "name": "init_tg_rt_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void init_tg_rt_entry(struct task_group * tg, struct rt_rq * rt_rq, struct sched_rt_entity * rt_se, int cpu, struct sched_rt_entity * parent)
```
</details>
</li>
</ul>
