# Function: <code>psi_show</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579826784,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:697",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826784,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856656,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:939",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856656,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905184,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905184,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579948741,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:989",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947248,
      "name": "psi_show.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071579950336,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579937109,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1005",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934960,
      "name": "psi_show.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    },
    {
      "addr": 18446744071579938896,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945968,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1033",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945968,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073024,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1048",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073024,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206080,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1046",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_show",
        "kernel/sched/build_utility.c:psi_memory_show",
        "kernel/sched/build_utility.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206080,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 677
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580397824,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1210",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_show",
        "kernel/sched/build_utility.c:psi_memory_show",
        "kernel/sched/build_utility.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397824,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580466272,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1233",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_show",
        "kernel/sched/build_utility.c:psi_memory_show",
        "kernel/sched/build_utility.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466272,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580526016,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:1225",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cpu_show",
        "kernel/sched/build_utility.c:psi_memory_show",
        "kernel/sched/build_utility.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526016,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491105064,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491105064,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225107948,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225107948,
      "name": "psi_show.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 3225110856,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283997136,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283997136,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271684516,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271684516,
      "name": "psi_show.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446743936271687808,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877296,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877296,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812288,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812288,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865456,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865456,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```

```json
{
  "name": "psi_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579910832,
      "name": "psi_show",
      "external": true,
      "loc": "kernel/sched/psi.c:940",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cpu_show",
        "kernel/sched/psi.c:psi_memory_show",
        "kernel/sched/psi.c:psi_io_show",
        "kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_memory_pressure_show",
        "kernel/cgroup/cgroup.c:cgroup_io_pressure_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910832,
      "name": "psi_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int psi_show(struct seq_file * m, struct psi_group * group, enum psi_res res)
```
</details>
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
