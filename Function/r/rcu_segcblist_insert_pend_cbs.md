# Function: <code>rcu_segcblist_insert_pend_cbs</code>

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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857952,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:368",
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
      "addr": 18446744071579857952,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899294,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:285",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898656,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933166,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:285",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932592,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980222,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:285",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979648,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020718,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:272",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020144,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071713,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071072,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130286,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:377",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129776,
      "name": "rcu_segcblist_insert_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108510,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:377",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107968,
      "name": "rcu_segcblist_insert_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112295,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:467",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111632,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254343,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:467",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253344,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423143,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:465",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422096,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580663127,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:465",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662032,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580739319,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:465",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738224,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824281,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:465",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nocb_do_flush_bypass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823200,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284880,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491284136,
      "name": "rcu_segcblist_insert_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291988,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225291132,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189712,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284188880,
      "name": "rcu_segcblist_insert_pend_cbs",
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801836,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271801272,
      "name": "rcu_segcblist_insert_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040449,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039808,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985759,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nocb_do_flush_bypass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985152,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031985,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031344,
      "name": "rcu_segcblist_insert_pend_cbs",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_segcblist_insert_pend_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082689,
      "name": "rcu_segcblist_insert_pend_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:396",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082048,
      "name": "rcu_segcblist_insert_pend_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist * rsclp, struct rcu_cblist * rclp)
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
