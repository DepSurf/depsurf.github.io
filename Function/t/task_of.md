# Function: <code>task_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575104,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:257",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575104,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579636707,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:257",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586128,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661280,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:272",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611920,
      "name": "task_of",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579635636,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:274",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589712,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579666528,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:276",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619120,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579701378,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:261",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:post_init_entity_util_avg"
      ],
      "caller_func": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650848,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579740003,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:258",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:post_init_entity_util_avg"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688208,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579769427,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721920,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579813287,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764544,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579853218,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:263",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798576,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579845368,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:261",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789760,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851864,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:271",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798256,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579957638,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1374",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895520,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071592108631,
      "name": "task_of.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1360",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580072317,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1360",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    },
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1360",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006384,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071593876277,
      "name": "task_of.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1406",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580242773,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1406",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    },
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1406",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168976,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071595978138,
      "name": "task_of.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_of",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1414",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580308741,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1414",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1414",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "task_of",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1433",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580361294,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1433",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/sched.h:1433",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490994324,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490944000,
      "name": "task_of",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225003912,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224962632,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283865128,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283800864,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271605642,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271574778,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789063,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740400,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579719847,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670784,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579773655,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724912,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
```

```json
{
  "name": "task_of",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579821735,
      "name": "task_of",
      "external": false,
      "loc": "kernel/sched/fair.c:251",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:pick_next_task_fair",
        "kernel/sched/fair.c:set_next_buddy",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:account_entity_dequeue",
        "kernel/sched/fair.c:account_entity_enqueue",
        "kernel/sched/fair.c:update_stats_enqueue_sleeper",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": [
        "kernel/sched/fair.c:check_preempt_wakeup",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772288,
      "name": "task_of",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct task_struct * task_of(struct sched_entity * se)
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
