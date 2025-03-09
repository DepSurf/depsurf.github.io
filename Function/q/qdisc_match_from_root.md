# Function: <code>qdisc_match_from_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586465888,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:260",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup",
        "net/sched/sch_api.c:qdisc_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586911968,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:258",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup",
        "net/sched/sch_api.c:qdisc_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587097424,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:259",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup",
        "net/sched/sch_api.c:qdisc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097424,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225984,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:268",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225984,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587741088,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:262",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741088,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588079040,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:262",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079040,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255760,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:261",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588255760,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588647040,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588647040,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588869408,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869408,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589753856,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:259",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589753856,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589788448,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:259",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788448,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589692432,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:259",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589692432,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590450160,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:259",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590450160,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592051936,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:259",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_tclass_root",
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592051936,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593870464,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:261",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_tclass_root",
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593870464,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594245408,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:261",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_tclass_root",
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594245408,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595042704,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:261",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_tclass_root",
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
        "net/sched/sch_api.c:qdisc_tree_reduce_backlog",
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595042704,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502457312,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502457312,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235172752,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235172752,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296009536,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296009536,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278642822,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278642822,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588475792,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475792,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588187792,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187792,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588807968,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807968,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```

```json
{
  "name": "qdisc_match_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588948624,
      "name": "qdisc_match_from_root",
      "external": false,
      "loc": "net/sched/sch_api.c:257",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:qdisc_lookup_rcu",
        "net/sched/sch_api.c:qdisc_lookup_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588948624,
      "name": "qdisc_match_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct Qdisc * qdisc_match_from_root(struct Qdisc * root, u32 handle)
```
</details>
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
