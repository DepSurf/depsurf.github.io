# Function: <code>_dev_pm_opp_cpumask_remove_table</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, bool of)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587061808,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:111",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587061808,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, bool of)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:111",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360162,
      "name": "_dev_pm_opp_cpumask_remove_table.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587360016,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:111",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540037,
      "name": "_dev_pm_opp_cpumask_remove_table.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587539888,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814881,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071587814688,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588020097,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588019888,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879585,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588879376,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591597640,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588892400,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591541231,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588781616,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592656121,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589473856,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594540815,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590952800,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592654832,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592654832,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593085600,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593085600,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593838000,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593838000,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501276528,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501276528,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233765808,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233765808,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294799936,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294799936,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277951330,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table",
        "drivers/opp/of.c:dev_pm_opp_of_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277951330,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587645089,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587644880,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587418961,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587418752,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976241,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587976032,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, int last_cpu)
```

```json
{
  "name": "_dev_pm_opp_cpumask_remove_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "external": true,
      "loc": "drivers/opp/cpu.c:108",
      "file": "drivers/opp/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/cpu.c:dev_pm_opp_cpumask_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091617,
      "name": "_dev_pm_opp_cpumask_remove_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588091408,
      "name": "_dev_pm_opp_cpumask_remove_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void _dev_pm_opp_cpumask_remove_table(const struct cpumask * cpumask, bool of)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int last_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>bool of</code>
</li>
</ul>
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
