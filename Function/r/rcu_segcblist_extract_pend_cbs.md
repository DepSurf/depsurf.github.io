# Function: <code>rcu_segcblist_extract_pend_cbs</code>

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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857744,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:314",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_dead_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857744,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898448,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:231",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898448,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932384,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:231",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932384,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979440,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:231",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979440,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580019936,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:218",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019936,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580070848,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070848,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580129568,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:326",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129568,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580107760,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:326",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107760,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111360,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:412",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111360,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580252912,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:412",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252912,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580421600,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:410",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580421600,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580661488,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:410",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661488,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580737680,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:410",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737680,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580822672,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:410",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822672,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491283824,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491283824,
      "name": "rcu_segcblist_extract_pend_cbs",
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225290848,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225290848,
      "name": "rcu_segcblist_extract_pend_cbs",
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284188624,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284188624,
      "name": "rcu_segcblist_extract_pend_cbs",
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801026,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271801026,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580039584,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039584,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984944,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984944,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031120,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031120,
      "name": "rcu_segcblist_extract_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_extract_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081824,
      "name": "rcu_segcblist_extract_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:343",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081824,
      "name": "rcu_segcblist_extract_pend_cbs",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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
