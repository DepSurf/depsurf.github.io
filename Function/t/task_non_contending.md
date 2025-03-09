# Function: <code>task_non_contending</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660080,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:204",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660080,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690240,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:205",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690240,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579727360,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:236",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727360,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763248,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763248,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790736,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
    },
    {
      "addr": 18446744071579801263,
      "name": "task_non_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837360,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837360,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876224,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876224,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579869344,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:314",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869344,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877296,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:314",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877296,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:314",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990528,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1397
    },
    {
      "addr": 18446744071592110973,
      "name": "task_non_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:388",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:switched_from_dl",
        "kernel/sched/build_policy.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099856,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
    },
    {
      "addr": 18446744071593878216,
      "name": "task_non_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:390",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:switched_from_dl",
        "kernel/sched/build_policy.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272624,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1395
    },
    {
      "addr": 18446744071595979982,
      "name": "task_non_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:392",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:switched_from_dl",
        "kernel/sched/build_policy.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341664,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1411
    },
    {
      "addr": 18446744071596498356,
      "name": "task_non_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void task_non_contending(struct sched_dl_entity * dl_se)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:407",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:switched_from_dl",
        "kernel/sched/build_policy.c:dl_server_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580394064,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1706
    },
    {
      "addr": 18446744071597395388,
      "name": "task_non_contending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491025816,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491025816,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1020
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225030828,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225030828,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283901664,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283901664,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271630860,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271630860,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809712,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809712,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579744208,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744208,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797728,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797728,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
void task_non_contending(struct task_struct * p)
```

```json
{
  "name": "task_non_contending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842704,
      "name": "task_non_contending",
      "external": false,
      "loc": "kernel/sched/deadline.c:237",
      "file": "kernel/sched/deadline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:switched_from_dl",
        "kernel/sched/deadline.c:dequeue_task_dl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842704,
      "name": "task_non_contending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 973
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
void task_non_contending(struct task_struct * p)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sched_dl_entity * dl_se</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * p</code>
</li>
</ul>
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
