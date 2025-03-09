# Function: <code>cgroup_kn_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980048,
      "name": "cgroup_kn_unlock",
      "external": false,
      "loc": "kernel/cgroup.c:1358",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_rmdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980048,
      "name": "cgroup_kn_unlock",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008736,
      "name": "cgroup_kn_unlock",
      "external": false,
      "loc": "kernel/cgroup.c:1413",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008736,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042336,
      "name": "cgroup_kn_unlock",
      "external": false,
      "loc": "kernel/cgroup.c:1418",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rmdir",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_release_agent_write",
        "kernel/cgroup.c:cgroup_kn_lock_live"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042336,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042224,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042224,
      "name": "cgroup_kn_unlock",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091728,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1481",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091728,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150816,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1484",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150816,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580198448,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1522",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198448,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245328,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245328,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293552,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293552,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364656,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1553",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364656,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351536,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1550",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351536,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580354656,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1551",
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
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354656,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580511712,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1582",
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
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511712,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708288,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1585",
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
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708288,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981632,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1619",
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
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981632,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069520,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1613",
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
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069520,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166992,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1608",
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
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166992,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491543680,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491543680,
      "name": "cgroup_kn_unlock",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225508548,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225508548,
      "name": "cgroup_kn_unlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284513664,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284513664,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271959268,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271959268,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580262352,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262352,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209856,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209856,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253600,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253600,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void cgroup_kn_unlock(struct kernfs_node * kn)
```

```json
{
  "name": "cgroup_kn_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306928,
      "name": "cgroup_kn_unlock",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1563",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_rmdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_freeze_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_max_depth_write",
        "kernel/cgroup/cgroup.c:cgroup_max_descendants_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306928,
      "name": "cgroup_kn_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
