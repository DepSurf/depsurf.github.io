# Function: <code>guarantee_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003904,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cpuset.c:336",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:cpuset_cpus_allowed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003904,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580037760,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cpuset.c:335",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_cpus_allowed",
        "kernel/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037760,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072784,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cpuset.c:335",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_cpus_allowed",
        "kernel/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072784,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580079568,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:338",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079568,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132576,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:349",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132576,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:349",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191824,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580205639,
      "name": "guarantee_online_cpus.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580239424,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:406",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239360,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580257911,
      "name": "guarantee_online_cpus.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580289931,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:368",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289872,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071580308938,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580338267,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338208,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071580357818,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:384",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411152,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071580430794,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:384",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398464,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071591315455,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:384",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399696,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071591257640,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void guarantee_online_cpus(struct task_struct * tsk, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:400",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563248,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071592161880,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void guarantee_online_cpus(struct task_struct * tsk, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:418",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768704,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071593935010,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void guarantee_online_cpus(struct task_struct * tsk, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581049824,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:501",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049824,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void guarantee_online_cpus(struct task_struct * tsk, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139584,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:501",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139584,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void guarantee_online_cpus(struct task_struct * tsk, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240592,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:531",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240592,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491601160,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491601160,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225559928,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225559928,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284587968,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284587968,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272003232,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272003232,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580307067,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307008,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071580326618,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254635,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254576,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071580273882,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580298315,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298256,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071580317866,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void guarantee_online_cpus(struct cpuset * cs, struct cpumask * pmask)
```

```json
{
  "name": "guarantee_online_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580352971,
      "name": "guarantee_online_cpus",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:380",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_cpus_allowed",
        "kernel/cgroup/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352912,
      "name": "guarantee_online_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071580372858,
      "name": "guarantee_online_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpuset * cs</code>
</li>
</ul>
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
