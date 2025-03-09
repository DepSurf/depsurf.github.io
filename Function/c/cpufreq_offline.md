# Function: <code>cpufreq_offline</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586259408,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1361",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_callback",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259408,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466368,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1329",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466368,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586590928,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1332",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590928,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074176,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1364",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074176,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1362",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372176,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071587377705,
      "name": "cpufreq_offline.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1367",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587552016,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071587557609,
      "name": "cpufreq_offline.cold.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1520",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826592,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071587833176,
      "name": "cpufreq_offline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588031616,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071588038123,
      "name": "cpufreq_offline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1551",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892784,
      "name": "cpufreq_offline.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071588898877,
      "name": "cpufreq_offline.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1557",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588910912,
      "name": "cpufreq_offline.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071591598397,
      "name": "cpufreq_offline.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1563",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588799088,
      "name": "cpufreq_offline.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    },
    {
      "addr": 18446744071591541979,
      "name": "cpufreq_offline.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1572",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589491664,
      "name": "cpufreq_offline.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 18446744071592657218,
      "name": "cpufreq_offline.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590971877,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1633",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592676389,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1630",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593107109,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1637",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593859925,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1678",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501294608,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    },
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq-dt.c:303",
      "file": "drivers/cpufreq/cpufreq-dt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501294608,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
    },
    {
      "addr": 18446603336501323232,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233783184,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    },
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq-dt.c:303",
      "file": "drivers/cpufreq/cpufreq-dt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233783184,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 3233809448,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294822240,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294822240,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587656608,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071587663115,
      "name": "cpufreq_offline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587430480,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071587436987,
      "name": "cpufreq_offline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987760,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071587994267,
      "name": "cpufreq_offline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int cpufreq_offline(unsigned int cpu)
```

```json
{
  "name": "cpufreq_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_offline",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:1534",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588103152,
      "name": "cpufreq_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    },
    {
      "addr": 18446744071588109691,
      "name": "cpufreq_offline.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void cpufreq_offline(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cpufreq_offline(unsigned int cpu)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpufreq_offline(unsigned int cpu)
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
