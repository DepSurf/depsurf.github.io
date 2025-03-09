# Function: <code>rcu_cblist_init</code>

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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856688,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:30",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856688,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579898993,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:31",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897744,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932895,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:31",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931680,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979951,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:31",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978736,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020447,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019216,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071407,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069696,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130121,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128640,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108345,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106832,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112192,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110272,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254240,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251584,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423014,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420032,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580662998,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659632,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580739190,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580735728,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824182,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_init_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820784,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284600,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491282096,
      "name": "rcu_cblist_init",
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291680,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225289368,
      "name": "rcu_cblist_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189368,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284187216,
      "name": "rcu_cblist_init",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801608,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271799700,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040143,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038432,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985487,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983872,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031679,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029968,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
```

```json
{
  "name": "rcu_cblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082383,
      "name": "rcu_cblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:18",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge",
        "kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080672,
      "name": "rcu_cblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void rcu_cblist_init(struct rcu_cblist * rclp)
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
