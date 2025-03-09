# Function: <code>timer_reduce</code>

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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579928736,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1107",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928736,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1017
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976448,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1115",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976448,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023680,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1114",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023680,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066512,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1109",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066512,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580115568,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115568,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580174800,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1125",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174800,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163472,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1119",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163472,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167056,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1121",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167056,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311760,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1121",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_process_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311760,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523600,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1174",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_route_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523600,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779200,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1214",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_key_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779200,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862192,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1214",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_key_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862192,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952336,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1214",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/cgroup/cgroup.c:cgroup_file_notify",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "net/mctp/route.c:mctp_alloc_local_tag",
        "net/mctp/route.c:mctp_key_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952336,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491332024,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491332024,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 892
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225327252,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225327252,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284260672,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284260672,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271832424,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271832424,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084768,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084768,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030896,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030896,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075840,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075840,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 809
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "timer_reduce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126912,
      "name": "timer_reduce",
      "external": true,
      "loc": "kernel/time/timer.c:1113",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/cgroup/cgroup.c:cgroup_file_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126912,
      "name": "timer_reduce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int timer_reduce(struct timer_list * timer, long unsigned int expires)
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
