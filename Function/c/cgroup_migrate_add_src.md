# Function: <code>cgroup_migrate_add_src</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579973216,
      "name": "cgroup_migrate_add_src",
      "external": false,
      "loc": "kernel/cgroup.c:2604",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973216,
      "name": "cgroup_migrate_add_src.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580027935,
      "name": "cgroup_migrate_add_src",
      "external": false,
      "loc": "kernel/cgroup.c:2660",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002896,
      "name": "cgroup_migrate_add_src.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580061967,
      "name": "cgroup_migrate_add_src",
      "external": false,
      "loc": "kernel/cgroup.c:2665",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034480,
      "name": "cgroup_migrate_add_src.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049217,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2234",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034768,
      "name": "cgroup_migrate_add_src.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071580043936,
      "name": "cgroup_migrate_add_src",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099185,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2443",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086480,
      "name": "cgroup_migrate_add_src.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580093408,
      "name": "cgroup_migrate_add_src",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580158291,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2461",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144480,
      "name": "cgroup_migrate_add_src.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580152496,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206035,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2502",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192320,
      "name": "cgroup_migrate_add_src.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580200144,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254148,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2645",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580238464,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071580267538,
      "name": "cgroup_migrate_add_src.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071580247216,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302404,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286656,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580295440,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372347,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2572",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357696,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071580366192,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580359227,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2568",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343984,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071580353136,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580362361,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2581",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347056,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    },
    {
      "addr": 18446744071580356256,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580513706,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2636",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592161039,
      "name": "cgroup_migrate_add_src.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580513648,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710257,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593934067,
      "name": "cgroup_migrate_add_src.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580710208,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580984449,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2744",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595999625,
      "name": "cgroup_migrate_add_src.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580984400,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581071969,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2713",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517759,
      "name": "cgroup_migrate_add_src.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581071920,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581169585,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2722",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597417981,
      "name": "cgroup_migrate_add_src.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581169536,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491553796,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491530856,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446603336491545800,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225514056,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225498636,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 3225510508,
      "name": "cgroup_migrate_add_src",
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284525588,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284498160,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 13835058055284516720,
      "name": "cgroup_migrate_add_src",
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271968026,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271950266,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446743936271961324,
      "name": "cgroup_migrate_add_src",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580271204,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255456,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580264240,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580218708,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203312,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580211744,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580262452,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246704,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580255488,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_add_src",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580315812,
      "name": "cgroup_migrate_add_src",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2646",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301584,
      "name": "cgroup_migrate_add_src.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071580308816,
      "name": "cgroup_migrate_add_src",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void cgroup_migrate_add_src(struct css_set * src_cset, struct cgroup * dst_cgrp, struct cgroup_mgctx * mgctx)
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
