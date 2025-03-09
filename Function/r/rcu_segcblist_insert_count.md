# Function: <code>rcu_segcblist_insert_count</code>

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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857824,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:332",
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
      "addr": 18446744071579857824,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899186,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:249",
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
      "addr": 18446744071579898528,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933058,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:249",
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
      "addr": 18446744071579932464,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980114,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:249",
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
      "addr": 18446744071579979520,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020610,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:236",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580020016,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071593,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580070928,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130187,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:344",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580129648,
      "name": "rcu_segcblist_insert_count",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108411,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:344",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580107840,
      "name": "rcu_segcblist_insert_count",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112236,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:434",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111488,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254284,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:434",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253136,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423084,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:432",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421856,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580663068,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:432",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661760,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580739260,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:432",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737952,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824252,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:432",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822944,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284776,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446603336491283936,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291856,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 3225290952,
      "name": "rcu_segcblist_insert_count",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189580,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 13835058055284188720,
      "name": "rcu_segcblist_insert_count",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801750,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446743936271801106,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040329,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580039664,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985655,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071579985024,
      "name": "rcu_segcblist_insert_count",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031865,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580031200,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082569,
      "name": "rcu_segcblist_insert_count",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:361",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580081904,
      "name": "rcu_segcblist_insert_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void rcu_segcblist_insert_count(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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
