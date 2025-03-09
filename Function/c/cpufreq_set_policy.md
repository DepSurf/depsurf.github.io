# Function: <code>cpufreq_set_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585859424,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2089",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859424,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263504,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2192",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263504,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586467872,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2164",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467872,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586592560,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2167",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592560,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075856,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2200",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075856,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373696,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2198",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373696,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587553536,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2199",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_update_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_max_freq",
        "drivers/cpufreq/cpufreq.c:store_scaling_min_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553536,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_policy * new_policy)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587828400,
      "name": "cpufreq_set_policy",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:2362",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828400,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 892
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033696,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033696,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894848,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2411",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894848,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588906832,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2488",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588906832,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588794992,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2494",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794992,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 789
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2496",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589487328,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071592657048,
      "name": "cpufreq_set_policy.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2536",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590968528,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1532
    },
    {
      "addr": 18446744071594541830,
      "name": "cpufreq_set_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2533",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592672832,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1509
    },
    {
      "addr": 18446744071596314077,
      "name": "cpufreq_set_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2540",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593103648,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1509
    },
    {
      "addr": 18446744071596842998,
      "name": "cpufreq_set_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2581",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593856416,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
    },
    {
      "addr": 18446744071597768144,
      "name": "cpufreq_set_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501300792,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501300792,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233789072,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233789072,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294831264,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294831264,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587658688,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587658688,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432560,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432560,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587989840,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989840,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
```

```json
{
  "name": "cpufreq_set_policy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105232,
      "name": "cpufreq_set_policy",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2374",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105232,
      "name": "cpufreq_set_policy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpufreq_governor * new_gov</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int new_pol</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpufreq_policy * new_policy</code>
</li>
</ul>
</details>
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
int cpufreq_set_policy(struct cpufreq_policy * policy, struct cpufreq_governor * new_gov, unsigned int new_pol)
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
