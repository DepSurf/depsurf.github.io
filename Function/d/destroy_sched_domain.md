# Function: <code>destroy_sched_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534134,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/core.c:5968",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain"
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
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579545317,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/core.c:5929",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567968,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/core.c:5950",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:cpu_attach_domain",
        "kernel/sched/core.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567968,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677024,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:345",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677024,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707728,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:363",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707728,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740736,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:355",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740736,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780496,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:549",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780496,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808192,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808192,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855712,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855712,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896048,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:576",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896048,
      "name": "destroy_sched_domain",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890752,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:604",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890752,
      "name": "destroy_sched_domain",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899152,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:604",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899152,
      "name": "destroy_sched_domain",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014384,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:604",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014384,
      "name": "destroy_sched_domain",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149728,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:624",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149728,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323184,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:624",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323184,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580390624,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:626",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390624,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446752,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:628",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:cpu_attach_domain",
        "kernel/sched/build_utility.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446752,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491052376,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491052376,
      "name": "destroy_sched_domain",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225057188,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225057188,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283929088,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283929088,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271647798,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271647798,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828064,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828064,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762640,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762640,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816080,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816080,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void destroy_sched_domain(struct sched_domain * sd)
```

```json
{
  "name": "destroy_sched_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861200,
      "name": "destroy_sched_domain",
      "external": false,
      "loc": "kernel/sched/topology.c:578",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:cpu_attach_domain",
        "kernel/sched/topology.c:destroy_sched_domains_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861200,
      "name": "destroy_sched_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void destroy_sched_domain(struct sched_domain * sd)
```
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
