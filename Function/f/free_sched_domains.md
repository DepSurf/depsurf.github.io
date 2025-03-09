# Function: <code>free_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565200,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/core.c:7074",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565200,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579576105,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/core.c:7009",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575440,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601360,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/core.c:7130",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains",
        "kernel/sched/core.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601360,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685680,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:1754",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685680,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716416,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:1769",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716416,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748128,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:1765",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748128,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788160,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2040",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788160,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815840,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2065",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815840,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863760,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863760,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905530,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2113",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904528,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900442,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2171",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899440,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579909517,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2199",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908544,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028387,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2328",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027360,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580201653,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2435",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200368,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580392665,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2442",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391328,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580461058,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2542",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459920,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580520728,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2587",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:alloc_sched_domains"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519568,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491062476,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491061712,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225065016,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225064156,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283941648,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283940608,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271654304,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271653478,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836112,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836112,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770688,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770688,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824128,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824128,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_sched_domains(cpumask_var_t * doms, unsigned int ndoms)
```

```json
{
  "name": "free_sched_domains",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869248,
      "name": "free_sched_domains",
      "external": true,
      "loc": "kernel/sched/topology.c:2128",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:alloc_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869248,
      "name": "free_sched_domains",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
