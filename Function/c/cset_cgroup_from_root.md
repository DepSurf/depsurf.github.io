# Function: <code>cset_cgroup_from_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579972352,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup.c:1176",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:proc_cgroup_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972352,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002720,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup.c:1250",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:proc_cgroup_show",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002720,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580034320,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup.c:1255",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:proc_cgroup_show",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034320,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580034432,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1148",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034432,
      "name": "cset_cgroup_from_root",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081952,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1317",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081952,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580141376,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1320",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141376,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580188160,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1355",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188160,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580234064,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234064,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282272,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282272,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580378060,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1387",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580348736,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580364988,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1384",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334960,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580368073,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1385",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580337696,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580533031,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1416",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580730371,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1419",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581006163,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1473",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581094777,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1467",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_path_ns",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581192109,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1461",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491530392,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491530392,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225498276,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225498276,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284490288,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284490288,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271949710,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271949710,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580251072,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580251072,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580198624,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198624,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580242320,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242320,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```

```json
{
  "name": "cset_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580296880,
      "name": "cset_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:1396",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/cgroup/cgroup.c:cgroup_path_ns_locked",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296880,
      "name": "cset_cgroup_from_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct cgroup * cset_cgroup_from_root(struct css_set * cset, struct cgroup_root * root)
```
</details>
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
