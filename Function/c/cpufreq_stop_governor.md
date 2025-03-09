# Function: <code>cpufreq_stop_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586255727,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2086",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255552,
      "name": "cpufreq_stop_governor.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586465799,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2058",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460256,
      "name": "cpufreq_stop_governor.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586592880,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2061",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584864,
      "name": "cpufreq_stop_governor.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587076197,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2094",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068160,
      "name": "cpufreq_stop_governor.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587365664,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2093",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365664,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587545552,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2094",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587545552,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587819968,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2244",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819968,
      "name": "cpufreq_stop_governor",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588024736,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024736,
      "name": "cpufreq_stop_governor",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588884512,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2295",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884512,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588906720,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2371",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588906720,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588794880,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2377",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794880,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589487262,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2379",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592657028,
      "name": "cpufreq_stop_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589487216,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590968448,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2419",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594541809,
      "name": "cpufreq_stop_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590968400,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592672720,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2416",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596314056,
      "name": "cpufreq_stop_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592672672,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593103536,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2423",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596842977,
      "name": "cpufreq_stop_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593103488,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593856304,
      "name": "cpufreq_stop_governor",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2464",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:__cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/intel_pstate.c:store_energy_performance_preference"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597768123,
      "name": "cpufreq_stop_governor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593856256,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501288152,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501288152,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233778580,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233778580,
      "name": "cpufreq_stop_governor",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294816208,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294816208,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587649728,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649728,
      "name": "cpufreq_stop_governor",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587423600,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587423600,
      "name": "cpufreq_stop_governor",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587980880,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587980880,
      "name": "cpufreq_stop_governor",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_stop_governor",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588096256,
      "name": "cpufreq_stop_governor",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2258",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_suspend",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588096256,
      "name": "cpufreq_stop_governor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void cpufreq_stop_governor(struct cpufreq_policy * policy)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpufreq_stop_governor(struct cpufreq_policy * policy)
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
