# Function: <code>reweight_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579585582,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2418",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_cfs_shares"
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
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579596707,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2542",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_cfs_shares"
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
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579630259,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2674",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_cfs_shares"
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
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579612322,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2746",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_cfs_shares"
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643888,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2782",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643888,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669728,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2810",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669728,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711680,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2791",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711680,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741632,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741632,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782352,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782352,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820768,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3082",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820768,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812064,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3096",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812064,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822720,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3093",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822720,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922656,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3083",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922656,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041872,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3110",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041872,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580205648,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3318",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205648,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263648,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3375",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263648,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580335536,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:3780",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580335536,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490961472,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490961472,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224970200,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224970200,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283825936,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283825936,
      "name": "reweight_entity",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271586816,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271586816,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758208,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758208,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688592,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688592,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742720,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742720,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
```

```json
{
  "name": "reweight_entity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791088,
      "name": "reweight_entity",
      "external": false,
      "loc": "kernel/sched/fair.c:2876",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_cfs_group",
        "kernel/sched/fair.c:reweight_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791088,
      "name": "reweight_entity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
void reweight_entity(struct cfs_rq * cfs_rq, struct sched_entity * se, long unsigned int weight, long unsigned int runnable)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int runnable</code>
</li>
</ul>
</details>
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
