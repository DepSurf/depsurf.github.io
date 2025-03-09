# Function: <code>detach_entity_cfs_rq</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579634058,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:9050",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq"
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
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579609187,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:9074",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642800,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:9547",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642800,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678208,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10054",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678208,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1556
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579705296,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10158",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705296,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752800,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10098",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752800,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795488,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795488,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818656,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10768",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818656,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810000,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10882",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810000,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816512,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10948",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816512,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:11314",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918064,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071592108875,
      "name": "detach_entity_cfs_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:11432",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:switched_from_fair",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030016,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
    },
    {
      "addr": 18446744071593876673,
      "name": "detach_entity_cfs_rq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580198958,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:11962",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq"
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
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580272046,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:12280",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq"
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
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580313285,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:12717",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:switched_from_fair"
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490965520,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490965520,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224975024,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224975024,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283840432,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283840432,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271583084,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271583084,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771344,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771344,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701936,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701936,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755856,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755856,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void detach_entity_cfs_rq(struct sched_entity * se)
```

```json
{
  "name": "detach_entity_cfs_rq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803728,
      "name": "detach_entity_cfs_rq",
      "external": false,
      "loc": "kernel/sched/fair.c:10083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:migrate_task_rq_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803728,
      "name": "detach_entity_cfs_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void detach_entity_cfs_rq(struct sched_entity * se)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void detach_entity_cfs_rq(struct sched_entity * se)
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
