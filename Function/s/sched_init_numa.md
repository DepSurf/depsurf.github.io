# Function: <code>sched_init_numa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595088442,
      "name": "sched_init_numa",
      "external": false,
      "loc": "kernel/sched/core.c:6644",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
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
  "name": "sched_init_numa",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595256061,
      "name": "sched_init_numa",
      "external": false,
      "loc": "kernel/sched/core.c:6610",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
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
  "name": "sched_init_numa",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595500682,
      "name": "sched_init_numa",
      "external": false,
      "loc": "kernel/sched/core.c:6707",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679584,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1327",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679584,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1452
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714448,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1330",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714448,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1325",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750255,
      "name": "sched_init_numa.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579746208,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1551
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1529",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790293,
      "name": "sched_init_numa.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579786192,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1554",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818086,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579813920,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866119,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579861696,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1540",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907314,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579902672,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1240
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1599",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284333,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579897568,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1633",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591227353,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579906720,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1203
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1764",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592113905,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071580024992,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1429
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
void sched_init_numa(int offline_node)
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1806",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/build_utility.c:sched_update_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593890960,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071580197424,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1449
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
void sched_init_numa(int offline_node)
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1806",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/build_utility.c:sched_update_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983197,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580388336,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1391
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
void sched_init_numa(int offline_node)
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1813",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/build_utility.c:sched_update_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501567,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580456928,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1391
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
void sched_init_numa(int offline_node)
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1839",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/build_utility.c:sched_update_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399253,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580516576,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1391
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491059384,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491059384,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1564
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": false,
      "loc": "kernel/sched/sched.h:1277",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283937632,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283937632,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2012
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": false,
      "loc": "kernel/sched/sched.h:1277",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838471,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579834048,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773047,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579768624,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826487,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579822064,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
void sched_init_numa()
```

```json
{
  "name": "sched_init_numa",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sched_init_numa",
      "external": true,
      "loc": "kernel/sched/topology.c:1555",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871623,
      "name": "sched_init_numa.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579867184,
      "name": "sched_init_numa",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1591
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void sched_init_numa()
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int offline_node</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void sched_init_numa()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void sched_init_numa()
```
</details>
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
