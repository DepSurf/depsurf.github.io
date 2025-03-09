# Function: <code>cgroup_migrate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987072,
      "name": "cgroup_migrate",
      "external": false,
      "loc": "kernel/cgroup.c:2716",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987072,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_root * root)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016560,
      "name": "cgroup_migrate",
      "external": false,
      "loc": "kernel/cgroup.c:2771",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016560,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_root * root)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050144,
      "name": "cgroup_migrate",
      "external": false,
      "loc": "kernel/cgroup.c:2776",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050144,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046144,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2351",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046144,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096016,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2560",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096016,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155232,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2578",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155232,
      "name": "cgroup_migrate",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202880,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202880,
      "name": "cgroup_migrate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580250208,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2759",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580250208,
      "name": "cgroup_migrate",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298448,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298448,
      "name": "cgroup_migrate",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369632,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2686",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369632,
      "name": "cgroup_migrate",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356544,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2682",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356544,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359744,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2695",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359744,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580517904,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2750",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517904,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714736,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714736,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989168,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2858",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989168,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076720,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2827",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076720,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174336,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2836",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174336,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491549272,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491549272,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225513708,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225513708,
      "name": "cgroup_migrate",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284520848,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284520848,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271964144,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271964144,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267248,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267248,
      "name": "cgroup_migrate",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580214752,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214752,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580258496,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258496,
      "name": "cgroup_migrate",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int cgroup_migrate(struct task_struct * leader, bool threadgroup, struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311840,
      "name": "cgroup_migrate",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311840,
      "name": "cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<code>struct cgroup_root * root</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup * cgrp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_mgctx * mgctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cgroup_root * root</code>
</li>
</ul>
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
