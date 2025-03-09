# Function: <code>cgroup_migrate_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cgroup_migrate_finish(struct list_head * preloaded_csets)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979888,
      "name": "cgroup_migrate_finish",
      "external": false,
      "loc": "kernel/cgroup.c:2572",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979888,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void cgroup_migrate_finish(struct list_head * preloaded_csets)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006656,
      "name": "cgroup_migrate_finish",
      "external": false,
      "loc": "kernel/cgroup.c:2627",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006656,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void cgroup_migrate_finish(struct list_head * preloaded_csets)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040272,
      "name": "cgroup_migrate_finish",
      "external": false,
      "loc": "kernel/cgroup.c:2632",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_transfer_tasks",
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_migrate_prepare_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040272,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043600,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2195",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043600,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093072,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2404",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093072,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152160,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2422",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152160,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199808,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2463",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199808,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580246880,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2606",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246880,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295104,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295104,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365856,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2533",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365856,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580352800,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2529",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352800,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355920,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2542",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355920,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513312,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2597",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513312,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709888,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2601",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709888,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984064,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2699",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984064,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071584,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2668",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071584,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169200,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2677",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169200,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491545488,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491545488,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225510180,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225510180,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284516288,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284516288,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271961024,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271961024,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263904,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263904,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211408,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211408,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255152,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255152,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
void cgroup_migrate_finish(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_finish",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308480,
      "name": "cgroup_migrate_finish",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2607",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308480,
      "name": "cgroup_migrate_finish",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_mgctx * mgctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head * preloaded_csets</code>
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
