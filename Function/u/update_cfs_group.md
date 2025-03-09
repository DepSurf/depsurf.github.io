# Function: <code>update_cfs_group</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644304,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:2985",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644304,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670160,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3013",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670160,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712112,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:2994",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712112,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742064,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742064,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782784,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782784,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821088,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3236",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821088,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812384,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3250",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812384,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579823040,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3247",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823040,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922928,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3237",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922928,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580042240,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3264",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042240,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580206032,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3472",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206032,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580264032,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3529",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264032,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336080,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3959",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336080,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490961896,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490961896,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224971060,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224971060,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283826480,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283826480,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271587296,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271587296,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758640,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758640,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689024,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689024,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579743152,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743152,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void update_cfs_group(struct sched_entity * se)
```

```json
{
  "name": "update_cfs_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791520,
      "name": "update_cfs_group",
      "external": false,
      "loc": "kernel/sched/fair.c:3079",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791520,
      "name": "update_cfs_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void update_cfs_group(struct sched_entity * se)
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
