# Function: <code>enqueue_rt_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579633523,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1227",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579648387,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1289",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579673059,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1288",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579647302,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579677974,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1290",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579709014,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1299",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579750550,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1299",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579779158,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1299",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822256,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822256,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579862034,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1341",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579854370,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1343",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579862594,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1343",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579974102,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1358",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580094576,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1506",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580266466,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1502",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580332516,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1502",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_task_rt"
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
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580388228,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1447",
      "file": "kernel/sched/build_policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_task_rt"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491006512,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491006512,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225016104,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225016104,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283881824,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283881824,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271614618,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271614618,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579796550,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729008,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729008,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782624,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/sched/rt.c:sched_rt_rq_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782624,
      "name": "enqueue_rt_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enqueue_rt_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579832742,
      "name": "enqueue_rt_entity",
      "external": false,
      "loc": "kernel/sched/rt.c:1300",
      "file": "kernel/sched/rt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:enqueue_task_rt"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity * rt_se, unsigned int flags)
```
</details>
</li>
</ul>
