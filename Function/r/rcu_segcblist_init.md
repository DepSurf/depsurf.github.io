# Function: <code>rcu_segcblist_init</code>

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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856864,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:80",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcu_init_percpu_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856864,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899333,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:63",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcu_init_percpu_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897840,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933192,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:63",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcu_init_percpu_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931776,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980248,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:63",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978832,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020744,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:50",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019312,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071739,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070096,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580130310,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:145",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_nodes",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128912,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108534,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:145",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_nodes",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107104,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112331,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:237",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_nodes",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110624,
      "name": "rcu_segcblist_init",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580254379,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:237",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_nodes",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251936,
      "name": "rcu_segcblist_init",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580423179,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:237",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/update.c:cblist_init_generic",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420464,
      "name": "rcu_segcblist_init",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580663163,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:237",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/update.c:cblist_init_generic",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660176,
      "name": "rcu_segcblist_init",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580739355,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:237",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/update.c:cblist_init_generic",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736368,
      "name": "rcu_segcblist_init",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580824317,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:237",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/rcu/update.c:cblist_init_generic",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821392,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284904,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491282664,
      "name": "rcu_segcblist_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225292016,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225289796,
      "name": "rcu_segcblist_init",
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189740,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284187600,
      "name": "rcu_segcblist_init",
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801856,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271800198,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040475,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038832,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985785,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcu_init_nohz",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984240,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580032011,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030368,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082715,
      "name": "rcu_segcblist_init",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:154",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:__call_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081072,
      "name": "rcu_segcblist_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void rcu_segcblist_init(struct rcu_segcblist * rsclp)
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
