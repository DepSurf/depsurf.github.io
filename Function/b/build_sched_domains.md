# Function: <code>build_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562304,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/core.c:6968",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562304,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2843
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572544,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/core.c:6903",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572544,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2843
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597888,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/core.c:7012",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597888,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682144,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1633",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682144,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3514
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579710032,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1648",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710032,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1643",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741968,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3956
    },
    {
      "addr": 18446744071579750157,
      "name": "build_sched_domains.cold.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1903",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781824,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4084
    },
    {
      "addr": 18446744071579790189,
      "name": "build_sched_domains.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1928",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810432,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3201
    },
    {
      "addr": 18446744071579817904,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857968,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3444
    },
    {
      "addr": 18446744071579866008,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1970",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901168,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
    },
    {
      "addr": 18446744071579907183,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2029",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896032,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071591284190,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2057",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904544,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1898
    },
    {
      "addr": 18446744071591227225,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2192",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022288,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2395
    },
    {
      "addr": 18446744071592113735,
      "name": "build_sched_domains.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2248",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194384,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2616
    },
    {
      "addr": 18446744071593890794,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2248",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385216,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2577
    },
    {
      "addr": 18446744071595983156,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2348",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453984,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2588
    },
    {
      "addr": 18446744071596501547,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:2383",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513584,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2629
    },
    {
      "addr": 18446744071597399233,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491054992,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491054992,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3904
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225059800,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225059800,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3952
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283932672,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283932672,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4396
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271649326,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271649326,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3790
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830320,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3444
    },
    {
      "addr": 18446744071579838360,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764896,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3444
    },
    {
      "addr": 18446744071579772936,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818336,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3444
    },
    {
      "addr": 18446744071579826376,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int build_sched_domains(const struct cpumask * cpu_map, struct sched_domain_attr * attr)
```

```json
{
  "name": "build_sched_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_sched_domains",
      "external": false,
      "loc": "kernel/sched/topology.c:1985",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:sched_init_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863456,
      "name": "build_sched_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3454
    },
    {
      "addr": 18446744071579871512,
      "name": "build_sched_domains.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
