# Function: <code>enqueue_dl_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579638809,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:933",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579654005,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:913",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678565,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:902",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579662116,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1364",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579692247,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1353",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579723215,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1412",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765519,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1411",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_task_dl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1410",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792752,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
    },
    {
      "addr": 18446744071579801321,
      "name": "enqueue_dl_entity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839376,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839376,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877840,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1445",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877840,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871040,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1522",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871040,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879024,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1501",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879024,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1501",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995056,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
    },
    {
      "addr": 18446744071592111449,
      "name": "enqueue_dl_entity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1639",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110880,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
    },
    {
      "addr": 18446744071593878907,
      "name": "enqueue_dl_entity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1640",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284272,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1713
    },
    {
      "addr": 18446744071595980709,
      "name": "enqueue_dl_entity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1631",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351584,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1760
    },
    {
      "addr": 18446744071596498891,
      "name": "enqueue_dl_entity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1705",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:dl_server_start",
        "kernel/sched/build_policy.c:update_curr_dl_se",
        "kernel/sched/build_policy.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406192,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3147
    },
    {
      "addr": 18446744071597396186,
      "name": "enqueue_dl_entity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491027960,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491027960,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1356
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225035300,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225035300,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2272
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283903664,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283903664,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1788
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271632560,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271632560,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811728,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811728,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746224,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746224,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1457
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799744,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799744,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```

```json
{
  "name": "enqueue_dl_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579844720,
      "name": "enqueue_dl_entity",
      "external": false,
      "loc": "kernel/sched/deadline.c:1443",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844720,
      "name": "enqueue_dl_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity * dl_se, struct sched_dl_entity * pi_se, int flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sched_dl_entity * pi_se</code>
</li>
<li>
<b>Param reordered. </b>
<code>dl_se, pi_se, flags</code> ➡️ <code>dl_se, flags</code>
</li>
</ul>
</details>
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
