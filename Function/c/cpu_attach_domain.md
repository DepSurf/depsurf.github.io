# Function: <code>cpu_attach_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534016,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/core.c:6026",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:build_sched_domains",
        "kernel/sched/core.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534016,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1479
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545200,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/core.c:5987",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545200,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570448,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/core.c:6031",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570448,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677680,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:426",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677680,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579708320,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:441",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708320,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1706
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:433",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741168,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
    },
    {
      "addr": 18446744071579749340,
      "name": "cpu_attach_domain.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 817
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:632",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780928,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
    },
    {
      "addr": 18446744071579789372,
      "name": "cpu_attach_domain.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 817
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809536,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
    },
    {
      "addr": 18446744071579817809,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857056,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071579865179,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:659",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900640,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071579907087,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:687",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895424,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    },
    {
      "addr": 18446744071591284094,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:687",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904032,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071591227129,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:687",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021664,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071592113564,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:707",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193712,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071593890627,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:707",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384464,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
    },
    {
      "addr": 18446744071595983067,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:709",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453216,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
    },
    {
      "addr": 18446744071596501487,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:725",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512832,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071597399173,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491054040,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491054040,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225058828,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225058828,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283931456,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283931456,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271648490,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271648490,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829408,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071579837531,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763984,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071579772107,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817424,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071579825547,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void cpu_attach_domain(struct sched_domain * sd, struct root_domain * rd, int cpu)
```

```json
{
  "name": "cpu_attach_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_attach_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:661",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579862544,
      "name": "cpu_attach_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    },
    {
      "addr": 18446744071579870683,
      "name": "cpu_attach_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
