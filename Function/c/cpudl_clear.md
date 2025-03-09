# Function: <code>cpudl_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689744,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:156",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689744,
      "name": "cpudl_clear",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675696,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:156",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675696,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706320,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:156",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706320,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739312,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:154",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739312,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779072,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:154",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779072,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807365,
      "name": "cpudl_clear.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579806720,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854288,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854288,
      "name": "cpudl_clear",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893600,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893600,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888320,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:174",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888320,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897504,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:174",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897504,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012608,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:174",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012608,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110464,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:173",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110464,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580283824,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:173",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580283824,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351136,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:173",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351136,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405744,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:173",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:rq_offline_dl",
        "kernel/sched/build_policy.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405744,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491050152,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491050152,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225055888,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225055888,
      "name": "cpudl_clear",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283926944,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283926944,
      "name": "cpudl_clear",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271646276,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271646276,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826640,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826640,
      "name": "cpudl_clear",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761216,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761216,
      "name": "cpudl_clear",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814656,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814656,
      "name": "cpudl_clear",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl * cp, int cpu)
```

```json
{
  "name": "cpudl_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859776,
      "name": "cpudl_clear",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:150",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859776,
      "name": "cpudl_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void cpudl_clear(struct cpudl * cp, int cpu)
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
