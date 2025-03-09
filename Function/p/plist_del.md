# Function: <code>plist_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582965504,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:put_prev_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:__unqueue_futex",
        "kernel/futex.c:futex_requeue",
        "mm/swapfile.c:scan_swap_map",
        "mm/swapfile.c:get_swap_page",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582965504,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252528,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:get_swap_page",
        "mm/swapfile.c:scan_swap_map",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252528,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367872,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:get_swap_page",
        "mm/swapfile.c:scan_swap_map",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367872,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216864,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:get_swap_pages",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216864,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766832,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766832,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589145664,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145664,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589380800,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:113",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380800,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589837856,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:set_curr_task_rt",
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837856,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590064000,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064000,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585060880,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585060880,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210176,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210176,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093168,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093168,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585540752,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540752,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586695520,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt",
        "kernel/sched/build_policy.c:dequeue_task_rt",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex/core.c:__futex_unqueue",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695520,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595856800,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt",
        "kernel/sched/build_policy.c:dequeue_task_rt",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex/core.c:__futex_unqueue",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595856800,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596373696,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt",
        "kernel/sched/build_policy.c:dequeue_task_rt",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex/core.c:__futex_unqueue",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373696,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597268944,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_policy.c:pick_next_task_rt",
        "kernel/sched/build_policy.c:dequeue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex/core.c:__futex_unqueue",
        "kernel/futex/requeue.c:futex_wait_requeue_pi",
        "kernel/futex/requeue.c:futex_requeue",
        "kernel/futex/requeue.c:futex_requeue",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597268944,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503841320,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503841320,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236460316,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236460316,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297692816,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297692816,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279731928,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279731928,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589666256,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589666256,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589392080,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392080,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109632,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109632,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void plist_del(struct plist_node * node, struct plist_head * head)
```

```json
{
  "name": "plist_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590159968,
      "name": "plist_del",
      "external": true,
      "loc": "lib/plist.c:112",
      "file": "lib/plist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/rt.c:pick_next_task_rt",
        "kernel/sched/rt.c:dequeue_task_rt",
        "kernel/sched/rt.c:enqueue_task_rt",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/power/qos.c:pm_qos_update_target",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:__unqueue_futex",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__del_from_avail_list",
        "lib/plist.c:plist_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590159968,
      "name": "plist_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
