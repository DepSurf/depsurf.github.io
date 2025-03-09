# Function: <code>cgroup_rstat_flush_locked</code>

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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580171248,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:149",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171248,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219136,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:149",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219136,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268032,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268032,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316192,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316192,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580388032,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:142",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388032,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374800,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:141",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374800,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580377536,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:148",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580377536,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538768,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:148",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538768,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1017
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736000,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:145",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736000,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012736,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:174",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_exit",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012736,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101312,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:174",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101312,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198720,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:226",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198720,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1494
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491570744,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491570744,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225534244,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225534244,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284549360,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284549360,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271982706,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271982706,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284992,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284992,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232400,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232400,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276240,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_hold",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276240,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
```

```json
{
  "name": "cgroup_rstat_flush_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330064,
      "name": "cgroup_rstat_flush_locked",
      "external": false,
      "loc": "kernel/cgroup/rstat.c:152",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush_irqsafe",
        "kernel/cgroup/rstat.c:cgroup_rstat_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330064,
      "name": "cgroup_rstat_flush_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
void cgroup_rstat_flush_locked(struct cgroup * cgrp, bool may_sleep)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool may_sleep</code>
</li>
</ul>
</details>
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
