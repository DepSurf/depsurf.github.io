# Function: <code>cpudl_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpudl_set(struct cpudl * cp, int cpu, u64 dl, int is_valid)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649568,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:132",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:rq_offline_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649568,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl, int is_valid)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665136,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:132",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665136,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689952,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:196",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689952,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675888,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:196",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675888,
      "name": "cpudl_set",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579706512,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:196",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706512,
      "name": "cpudl_set",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739504,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:194",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739504,
      "name": "cpudl_set",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779264,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:194",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779264,
      "name": "cpudl_set",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807384,
      "name": "cpudl_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579806912,
      "name": "cpudl_set",
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854480,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854480,
      "name": "cpudl_set",
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893792,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893792,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888512,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:214",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888512,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897696,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:214",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897696,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012800,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:214",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:__enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012800,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110672,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:213",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110672,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284048,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:213",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284048,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351360,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:213",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351360,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405968,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:213",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405968,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491050544,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491050544,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225056144,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225056144,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283927280,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283927280,
      "name": "cpudl_set",
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271646520,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271646520,
      "name": "cpudl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826832,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826832,
      "name": "cpudl_set",
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761408,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761408,
      "name": "cpudl_set",
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579814848,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814848,
      "name": "cpudl_set",
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
void cpudl_set(struct cpudl * cp, int cpu, u64 dl)
```

```json
{
  "name": "cpudl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859968,
      "name": "cpudl_set",
      "external": true,
      "loc": "kernel/sched/cpudeadline.c:190",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859968,
      "name": "cpudl_set",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int is_valid</code>
</li>
</ul>
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
