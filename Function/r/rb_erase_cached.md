# Function: <code>rb_erase_cached</code>

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
void rb_erase_cached(struct rb_node * node, struct rb_root_cached * root)
```

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588782368,
      "name": "rb_erase_cached",
      "external": true,
      "loc": "lib/rbtree.c:474",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "fs/eventpoll.c:ep_remove",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "block/cfq-iosched.c:cfq_rb_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782368,
      "name": "rb_erase_cached",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
void rb_erase_cached(struct rb_node * node, struct rb_root_cached * root)
```

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589160656,
      "name": "rb_erase_cached",
      "external": true,
      "loc": "lib/rbtree.c:474",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "block/cfq-iosched.c:cfq_rb_erase"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589160656,
      "name": "rb_erase_cached",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
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
void rb_erase_cached(struct rb_node * node, struct rb_root_cached * root)
```

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589390592,
      "name": "rb_erase_cached",
      "external": true,
      "loc": "lib/rbtree.c:474",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589390592,
      "name": "rb_erase_cached",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 922
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579745509,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785788,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868807,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125718,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033362,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579793429,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831900,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917431,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202934,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137170,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590087970,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579838869,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869004,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962263,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441797,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584541905,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085890,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579831149,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861772,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950407,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494205,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584651905,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235010,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579829929,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:146",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883434,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:146",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dequeue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591652935,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:146",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521705,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:146",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584679064,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:146",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117826,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:146",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579930920,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999162,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:dequeue_task_dl",
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592825783,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837673,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100835,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566546,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580044912,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580114832,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594733587,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397590,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585833408,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586720162,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580209696,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580288001,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596485331,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984006,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586611529,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595882738,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580273019,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355361,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:__dequeue_task_dl",
        "kernel/sched/build_policy.c:__dequeue_task_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597026874,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582126535,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_rbtree_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208280,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586869924,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596400146,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580410907,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:__dequeue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597956218,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267459,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_rbtree_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584422776,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147809,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592088974,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "drivers/gpu/drm/drm_mm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mm.c:rm_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597295250,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:119",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490967016,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491019864,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491121916,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493761184,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495987600,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503866136,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224976492,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 3225024604,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3225122572,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 3227284440,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3229328020,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236494008,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283831000,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283893120,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284013072,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287380464,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290212492,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297725904,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271585288,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271624044,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271695910,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273367768,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275085930,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279762094,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579769285,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804252,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889543,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171670,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584105906,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589690226,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699877,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738654,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824503,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111110,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584041586,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589416018,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579753797,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792268,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579877703,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162150,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584089666,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590133602,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rb_erase_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579801637,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837260,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__dequeue_dl_entity",
        "kernel/sched/deadline.c:dequeue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923335,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:mark_wakeup_next_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238434,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192082,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590183986,
      "name": "rb_erase_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:144",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_del"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void rb_erase_cached(struct rb_node * node, struct rb_root_cached * root)
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void rb_erase_cached(struct rb_node * node, struct rb_root_cached * root)
```
</details>
</li>
</ul>
