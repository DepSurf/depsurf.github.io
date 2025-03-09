# Function: <code>rcu_segcblist_advance</code>

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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858000,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:383",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858000,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898704,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:300",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898704,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932640,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:300",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932640,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979696,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:300",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979696,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020192,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:287",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020192,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071120,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071120,
      "name": "rcu_segcblist_advance",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129824,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:390",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129824,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108016,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:390",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108016,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111680,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:482",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111680,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253392,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:482",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253392,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580422160,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:480",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422160,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662112,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:480",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662112,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738304,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:480",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738304,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823280,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:480",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_invoke_cbs",
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:__note_gp_changes",
        "kernel/rcu/tree.c:rcu_advance_cbs_nowake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823280,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491284208,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491284208,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225291196,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225291196,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284188944,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284188944,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271801332,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:__note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271801332,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039856,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039856,
      "name": "rcu_segcblist_advance",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985200,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985200,
      "name": "rcu_segcblist_advance",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580031392,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031392,
      "name": "rcu_segcblist_advance",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
```

```json
{
  "name": "rcu_segcblist_advance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082096,
      "name": "rcu_segcblist_advance",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:411",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/tree.c:rcu_advance_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082096,
      "name": "rcu_segcblist_advance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void rcu_segcblist_advance(struct rcu_segcblist * rsclp, long unsigned int seq)
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
