# Function: <code>sched_setattr_nocheck</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637072,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4427",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637072,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674752,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4412",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674752,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706672,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:4849",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706672,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748768,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748768,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784480,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5297",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784480,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579756576,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:6072",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775104,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579763728,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:6373",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783712,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579849872,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7536",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_normal"
      ],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849792,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579967184,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7644",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_normal"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967088,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580126896,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7786",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_normal"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126784,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580188960,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7895",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_normal"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188848,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236112,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:7956",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_set_normal"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sugov_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236000,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490927400,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490927400,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224945188,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224945188,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283780480,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283780480,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271562908,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271562908,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724720,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724720,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653280,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653280,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711472,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711472,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```

```json
{
  "name": "sched_setattr_nocheck",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756400,
      "name": "sched_setattr_nocheck",
      "external": true,
      "loc": "kernel/sched/core.c:5064",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756400,
      "name": "sched_setattr_nocheck",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int sched_setattr_nocheck(struct task_struct * p, const struct sched_attr * attr)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
