# Function: <code>cpupri_find_fitness</code>

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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892096,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:120",
      "file": "kernel/sched/cpupri.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892096,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886704,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:144",
      "file": "kernel/sched/cpupri.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886704,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895888,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:144",
      "file": "kernel/sched/cpupri.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895888,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010672,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:144",
      "file": "kernel/sched/cpupri.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:find_lowest_rq",
        "kernel/sched/cpupri.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010672,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580191888,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:143",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_lowest_rq",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191888,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580382464,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:143",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_lowest_rq",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382464,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451152,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:143",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_lowest_rq",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451152,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
```

```json
{
  "name": "cpupri_find_fitness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580510736,
      "name": "cpupri_find_fitness",
      "external": true,
      "loc": "kernel/sched/cpupri.c:144",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:find_lowest_rq",
        "kernel/sched/build_utility.c:cpupri_find_fitness"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580510736,
      "name": "cpupri_find_fitness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int cpupri_find_fitness(struct cpupri * cp, struct task_struct * p, struct cpumask * lowest_mask, bool (*)(struct task_struct *, int) fitness_fn)
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
