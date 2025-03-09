# Function: <code>rcu_segcblist_extract_done_cbs</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857648,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:291",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcutree_dead_cpu",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857648,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899039,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:208",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898352,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932972,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:208",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932288,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980028,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:208",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979344,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020524,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:195",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019840,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071503,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070752,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580129472,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:303",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129472,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580107664,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:303",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107664,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111248,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:387",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111248,
      "name": "rcu_segcblist_extract_done_cbs",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580252720,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:387",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252720,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421392,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:385",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421392,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661264,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:385",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661264,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580737456,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:385",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737456,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580822448,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:385",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822448,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284652,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491283688,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291756,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225290724,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189448,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284188496,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801668,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271800930,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040239,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039488,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985565,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984848,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031775,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031024,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082479,
      "name": "rcu_segcblist_extract_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:320",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081728,
      "name": "rcu_segcblist_extract_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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
