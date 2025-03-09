# Function: <code>set_rq_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579529216,
      "name": "set_rq_online",
      "external": false,
      "loc": "kernel/sched/core.c:5483",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:rq_attach_root",
        "kernel/sched/core.c:migration_call"
      ],
      "caller_func": [
        "kernel/sched/core.c:rq_attach_root",
        "kernel/sched/core.c:migration_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529216,
      "name": "set_rq_online.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579576449,
      "name": "set_rq_online",
      "external": false,
      "loc": "kernel/sched/core.c:5567",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544048,
      "name": "set_rq_online.part.50",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602548,
      "name": "set_rq_online",
      "external": false,
      "loc": "kernel/sched/core.c:5601",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568864,
      "name": "set_rq_online.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581081,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:5482",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553744,
      "name": "set_rq_online.part.81",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071579580928,
      "name": "set_rq_online",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579610425,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:5561",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582080,
      "name": "set_rq_online.part.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579610272,
      "name": "set_rq_online",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640346,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:5687",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611760,
      "name": "set_rq_online.part.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579640064,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579678006,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:5670",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649792,
      "name": "set_rq_online.part.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071579677728,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579710803,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6122",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673664,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579710608,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753155,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711248,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579752960,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787916,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6546",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751440,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579787696,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579779099,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:7380",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737312,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579778832,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787243,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:7749",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742848,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579786976,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579881883,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:8946",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824416,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071579881536,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999072,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:9234",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941184,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071579998736,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161200,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:9424",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097776,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580160832,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580209456,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:9568",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155744,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580209088,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580257776,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:9557",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200640,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071580257408,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490930976,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490894040,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336490930520,
      "name": "set_rq_online",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224949736,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224906540,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3224949500,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283785800,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283730176,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 13835058055283785472,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271566596,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271540174,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446743936271566252,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729075,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687424,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579728880,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579657683,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615888,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579657488,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579714723,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684464,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579714528,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_online(struct rq * rq)
```

```json
{
  "name": "set_rq_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579760819,
      "name": "set_rq_online",
      "external": true,
      "loc": "kernel/sched/core.c:6311",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719680,
      "name": "set_rq_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579760624,
      "name": "set_rq_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void set_rq_online(struct rq * rq)
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
