# Function: <code>register_sched_domain_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524656,
      "name": "register_sched_domain_sysctl",
      "external": false,
      "loc": "kernel/sched/core.c:5442",
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
      "addr": 18446744071579524656,
      "name": "register_sched_domain_sysctl",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677504,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:330",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579677504,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702128,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:330",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579702128,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1407
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698320,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:331",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579698320,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1361
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729472,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:338",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579729472,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1641
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:313",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579770327,
      "name": "register_sched_domain_sysctl.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579759264,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:314",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579813159,
      "name": "register_sched_domain_sysctl.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579802144,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579841087,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579830672,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1265
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579889381,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579878976,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579932189,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579922528,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:351",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071591287297,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579916400,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491080256,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446603336491080256,
      "name": "register_sched_domain_sysctl",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225084420,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 3225084420,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283964816,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 13835058055283964816,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1668
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271669332,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446743936271669332,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1082
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579861509,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579851120,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579796437,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579786032,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579849749,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579839344,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
void register_sched_domain_sysctl()
```

```json
{
  "name": "register_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:297",
      "file": "kernel/sched/debug.c",
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
      "addr": 18446744071579894805,
      "name": "register_sched_domain_sysctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579884400,
      "name": "register_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void register_sched_domain_sysctl()
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
