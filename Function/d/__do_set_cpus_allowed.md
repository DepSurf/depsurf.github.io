# Function: <code>__do_set_cpus_allowed</code>

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
void __do_set_cpus_allowed(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747168,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2066",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747168,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
void __do_set_cpus_allowed(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752688,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2073",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752688,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __do_set_cpus_allowed(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2451",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836400,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
    },
    {
      "addr": 18446744071592107055,
      "name": "__do_set_cpus_allowed.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __do_set_cpus_allowed(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2550",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950576,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
    },
    {
      "addr": 18446744071593874759,
      "name": "__do_set_cpus_allowed.cold",
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
void __do_set_cpus_allowed(struct task_struct * p, struct affinity_context * ctx)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2552",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109616,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    },
    {
      "addr": 18446744071595977140,
      "name": "__do_set_cpus_allowed.cold",
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
void __do_set_cpus_allowed(struct task_struct * p, struct affinity_context * ctx)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2728",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171568,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    },
    {
      "addr": 18446744071596495008,
      "name": "__do_set_cpus_allowed.cold",
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
void __do_set_cpus_allowed(struct task_struct * p, struct affinity_context * ctx)
```

```json
{
  "name": "__do_set_cpus_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_set_cpus_allowed",
      "external": false,
      "loc": "kernel/sched/core.c:2756",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:__set_cpus_allowed_ptr_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217936,
      "name": "__do_set_cpus_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    },
    {
      "addr": 18446744071597391811,
      "name": "__do_set_cpus_allowed.cold",
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __do_set_cpus_allowed(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct affinity_context * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask * new_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
