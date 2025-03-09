# Function: <code>task_contending</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579656912,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:258",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656912,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579687664,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:259",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687664,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579722592,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722592,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579764896,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:294",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764896,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789760,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789760,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836896,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836896,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872384,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872384,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865392,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:370",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865392,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873504,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:370",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873504,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579987053,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:370",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986816,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    },
    {
      "addr": 18446744071592110572,
      "name": "task_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098201,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:444",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097952,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    },
    {
      "addr": 18446744071593877938,
      "name": "task_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580270937,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:446",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270688,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    },
    {
      "addr": 18446744071595979704,
      "name": "task_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580336345,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:448",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336096,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071596497886,
      "name": "task_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:471",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390240,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    },
    {
      "addr": 18446744071597395110,
      "name": "task_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491025336,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491025336,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225030168,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225030168,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283900912,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283900912,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271624692,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271624692,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809248,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809248,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743744,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743744,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797264,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797264,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
```

```json
{
  "name": "task_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842240,
      "name": "task_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:293",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842240,
      "name": "task_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void task_contending(struct sched_dl_entity * dl_se, int flags)
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
