# Function: <code>cgroup_migrate_prepare_dst</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup * dst_cgrp, struct list_head * preloaded_csets)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982592,
      "name": "cgroup_migrate_prepare_dst",
      "external": false,
      "loc": "kernel/cgroup.c:2643",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_attach_task",
        "kernel/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982592,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int cgroup_migrate_prepare_dst(struct list_head * preloaded_csets)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010592,
      "name": "cgroup_migrate_prepare_dst",
      "external": false,
      "loc": "kernel/cgroup.c:2707",
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
      "addr": 18446744071580010592,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int cgroup_migrate_prepare_dst(struct list_head * preloaded_csets)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044176,
      "name": "cgroup_migrate_prepare_dst",
      "external": false,
      "loc": "kernel/cgroup.c:2712",
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
      "addr": 18446744071580044176,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580043968,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2281",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043968,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093440,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2490",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093440,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152528,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2508",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152528,
      "name": "cgroup_migrate_prepare_dst",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580200176,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2549",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200176,
      "name": "cgroup_migrate_prepare_dst",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247248,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2692",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247248,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295472,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295472,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580366224,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2619",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580366224,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580353168,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2615",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353168,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356288,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2628",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356288,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514032,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2683",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514032,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710624,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710624,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984832,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2791",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984832,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072352,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2760",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072352,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169968,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2769",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169968,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491545880,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491545880,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225510548,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
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
      "addr": 3225510548,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284516752,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284516752,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271961388,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271961388,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264272,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264272,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211776,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211776,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580255520,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255520,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int cgroup_migrate_prepare_dst(struct cgroup_mgctx * mgctx)
```

```json
{
  "name": "cgroup_migrate_prepare_dst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308848,
      "name": "cgroup_migrate_prepare_dst",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:2693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_update_dfl_csses",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308848,
      "name": "cgroup_migrate_prepare_dst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
<b>Param removed. </b>
<code>struct cgroup * dst_cgrp</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_cgrp, preloaded_csets</code> ➡️ <code>preloaded_csets</code>
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
