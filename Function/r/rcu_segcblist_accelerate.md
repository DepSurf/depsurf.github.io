# Function: <code>rcu_segcblist_accelerate</code>

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
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858096,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:438",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858096,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898800,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:355",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898800,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932736,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:355",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932736,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979792,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:355",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979792,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020288,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:342",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020288,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071232,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071232,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129936,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:445",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129936,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108128,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:445",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108128,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111872,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:539",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111872,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253600,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:539",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253600,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580422384,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:537",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422384,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662352,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:537",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662352,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738544,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:537",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738544,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823520,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:537",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823520,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491284376,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491284376,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225291404,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225291404,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284189120,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284189120,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271801450,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271801450,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039968,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039968,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985312,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985312,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031504,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031504,
      "name": "rcu_segcblist_accelerate",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_accelerate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082208,
      "name": "rcu_segcblist_accelerate",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:466",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082208,
      "name": "rcu_segcblist_accelerate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
bool rcu_segcblist_accelerate(struct rcu_segcblist * rsclp, long unsigned int seq)
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
