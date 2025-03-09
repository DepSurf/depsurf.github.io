# Function: <code>cpuset_hotplug_update_tasks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580012508,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cpuset.c:2220",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580044620,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cpuset.c:2241",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580083111,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cpuset.c:2241",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580088874,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2227",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580141966,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2237",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2238",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2974",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2929",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295456,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2357
    },
    {
      "addr": 18446744071580308974,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343808,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2353
    },
    {
      "addr": 18446744071580357854,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580426160,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3019",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426160,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580413648,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3042",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413648,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3042",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413648,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2409
    },
    {
      "addr": 18446744071591257714,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3099",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577936,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2508
    },
    {
      "addr": 18446744071592161954,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3139",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778816,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2524
    },
    {
      "addr": 18446744071593935034,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061280,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3413",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061280,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3173
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152480,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3602",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152480,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2352
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258512,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:4456",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258512,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1857
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491607584,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491607584,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225569732,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225569732,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284591856,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284591856,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1948
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
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272011750,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272011750,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312608,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2353
    },
    {
      "addr": 18446744071580326654,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259936,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2341
    },
    {
      "addr": 18446744071580273918,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303856,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2353
    },
    {
      "addr": 18446744071580317902,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```

```json
{
  "name": "cpuset_hotplug_update_tasks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpuset_hotplug_update_tasks",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:3017",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358304,
      "name": "cpuset_hotplug_update_tasks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2330
    },
    {
      "addr": 18446744071580372894,
      "name": "cpuset_hotplug_update_tasks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void cpuset_hotplug_update_tasks(struct cpuset * cs, struct tmpmasks * tmp)
```
</details>
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
