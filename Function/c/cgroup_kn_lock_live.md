# Function: <code>cgroup_kn_lock_live</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980176,
      "name": "cgroup_kn_lock_live",
      "external": false,
      "loc": "kernel/cgroup.c:1388",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980176,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014208,
      "name": "cgroup_kn_lock_live",
      "external": false,
      "loc": "kernel/cgroup.c:1445",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014208,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047792,
      "name": "cgroup_kn_lock_live",
      "external": false,
      "loc": "kernel/cgroup.c:1450",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047792,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052896,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1342",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052896,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102848,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1513",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102848,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161888,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1516",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161888,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209680,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1554",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209680,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257776,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257776,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306000,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306000,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375792,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1585",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375792,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580362640,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1582",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580362640,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365696,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1583",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365696,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580525344,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1614",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525344,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722192,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1617",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722192,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997056,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1651",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997056,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085616,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1645",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085616,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183136,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1640",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183136,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491557744,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491557744,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225522248,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225522248,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284531152,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284531152,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271971794,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271971794,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580274800,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274800,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580222304,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580222304,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266048,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266048,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct cgroup * cgroup_kn_lock_live(struct kernfs_node * kn, bool drain_offline)
```

```json
{
  "name": "cgroup_kn_lock_live",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319424,
      "name": "cgroup_kn_lock_live",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1595",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319424,
      "name": "cgroup_kn_lock_live",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool drain_offline</code>
</li>
</ul>
</details>
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
