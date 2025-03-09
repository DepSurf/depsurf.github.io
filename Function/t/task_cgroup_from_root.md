# Function: <code>task_cgroup_from_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972755,
      "name": "task_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup.c:1207",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:task_cgroup_path",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup.c:proc_cgroup_show"
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
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580028914,
      "name": "task_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup.c:1281",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:proc_cgroup_show",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:task_cgroup_path"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580063058,
      "name": "task_cgroup_from_root",
      "external": false,
      "loc": "kernel/cgroup.c:1286",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:proc_cgroup_show",
        "kernel/cgroup.c:cgroup_attach_task_all",
        "kernel/cgroup.c:task_cgroup_path"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580058377,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1179",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042192,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580109116,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1350",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091696,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580168284,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1353",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150784,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580216204,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1388",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198416,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580264185,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245296,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580312489,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293520,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580382521,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1420",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364624,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580369433,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1417",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351504,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580372457,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354624,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580533020,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511600,
      "name": "task_cgroup_from_root",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580730360,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1452",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708160,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581006152,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1486",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981488,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581094766,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1480",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069376,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581192098,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1475",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:task_get_cgroup1",
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166816,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491565272,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491543624,
      "name": "task_cgroup_from_root",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225529604,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225508516,
      "name": "task_cgroup_from_root",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284543524,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284513632,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271978554,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271959212,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580281289,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262320,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580228729,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209824,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580272537,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253568,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
```

```json
{
  "name": "task_cgroup_from_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580326073,
      "name": "task_cgroup_from_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1429",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:task_cgroup_path"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_attach_task_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306896,
      "name": "task_cgroup_from_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
struct cgroup * task_cgroup_from_root(struct task_struct * task, struct cgroup_root * root)
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
