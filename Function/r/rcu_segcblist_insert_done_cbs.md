# Function: <code>rcu_segcblist_insert_done_cbs</code>

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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857872,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:346",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_dead_cpu",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857872,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899204,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:263",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898576,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933102,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:263",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932512,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980158,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:263",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979568,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020654,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:250",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020064,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071649,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070992,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130224,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:355",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129696,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108448,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:355",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107888,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111536,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:444",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111536,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580253184,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:444",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253184,
      "name": "rcu_segcblist_insert_done_cbs",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421904,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:442",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421904,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661824,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:442",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661824,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738016,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:442",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738016,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580822992,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:442",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822992,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284820,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491284024,
      "name": "rcu_segcblist_insert_done_cbs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291916,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225291028,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189636,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284188784,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801786,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271801184,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040385,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039728,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985695,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985072,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031921,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031264,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_done_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082625,
      "name": "rcu_segcblist_insert_done_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:374",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081968,
      "name": "rcu_segcblist_insert_done_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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
