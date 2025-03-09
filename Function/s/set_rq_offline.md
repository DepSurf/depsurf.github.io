# Function: <code>set_rq_offline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527472,
      "name": "set_rq_offline",
      "external": false,
      "loc": "kernel/sched/core.c:5498",
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
      "addr": 18446744071579527472,
      "name": "set_rq_offline.part.47",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579577303,
      "name": "set_rq_offline",
      "external": false,
      "loc": "kernel/sched/core.c:5582",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543952,
      "name": "set_rq_offline.part.51",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603386,
      "name": "set_rq_offline",
      "external": false,
      "loc": "kernel/sched/core.c:5616",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:rq_attach_root"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568768,
      "name": "set_rq_offline.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581632,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:5497",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552688,
      "name": "set_rq_offline.part.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071579580960,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579610973,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:5576",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581952,
      "name": "set_rq_offline.part.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071579610304,
      "name": "set_rq_offline",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640096,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:5702",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640096,
      "name": "set_rq_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579677760,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:5685",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677760,
      "name": "set_rq_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579711291,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6137",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672736,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071579710640,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753647,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579710720,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071579752992,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788373,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6561",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751200,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071579787728,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579779472,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:7395",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737056,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579778864,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787624,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:7764",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742720,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579787008,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882583,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:8961",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824160,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579881568,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999528,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:9249",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941312,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071579998784,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161652,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:9439",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097920,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071580160896,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580209927,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:9583",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183664,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071580209152,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580258247,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:9572",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/build_utility.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230816,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071580257472,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490931656,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490893896,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446603336490930584,
      "name": "set_rq_offline",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224950276,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224906640,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3224949540,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283786796,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283730384,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 13835058055283785504,
      "name": "set_rq_offline",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271566304,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271566304,
      "name": "set_rq_offline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729567,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686912,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071579728912,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579658351,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615360,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071579657520,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715215,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683936,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071579714560,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
```

```json
{
  "name": "set_rq_offline",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579761306,
      "name": "set_rq_offline",
      "external": true,
      "loc": "kernel/sched/core.c:6326",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_dying"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/topology.c:rq_attach_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719328,
      "name": "set_rq_offline.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071579760656,
      "name": "set_rq_offline",
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
void set_rq_offline(struct rq * rq)
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
