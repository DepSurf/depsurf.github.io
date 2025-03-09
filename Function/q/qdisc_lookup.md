# Function: <code>qdisc_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586465872,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:296",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586465872,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586911952,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:294",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586911952,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587106384,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:298",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106384,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587234704,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:306",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234704,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750192,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:300",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750192,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588088768,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:300",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088768,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588265744,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:299",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265744,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588657344,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657344,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588879728,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879728,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589766052,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:297",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770592,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589800660,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:298",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589805328,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589705200,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:298",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589710000,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590463408,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:298",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590468192,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592065439,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:298",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592070720,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593885371,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:300",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593890464,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594260573,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:300",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594265808,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595057806,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:300",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog"
      ],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595063696,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502469416,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502469416,
      "name": "qdisc_lookup",
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235183944,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235183944,
      "name": "qdisc_lookup",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296025504,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296025504,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278651888,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278651888,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588486112,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588486112,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588198112,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198112,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588818288,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818288,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct Qdisc * qdisc_lookup(struct net_device * dev, u32 handle)
```

```json
{
  "name": "qdisc_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958896,
      "name": "qdisc_lookup",
      "external": true,
      "loc": "net/sched/sch_api.c:295",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958896,
      "name": "qdisc_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
