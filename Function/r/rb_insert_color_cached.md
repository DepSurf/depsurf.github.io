# Function: <code>rb_insert_color_cached</code>

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
void rb_insert_color_cached(struct rb_node * node, struct rb_root_cached * root, bool leftmost)
```

```json
{
  "name": "rb_insert_color_cached",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781280,
      "name": "rb_insert_color_cached",
      "external": true,
      "loc": "lib/rbtree.c:466",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "fs/eventpoll.c:SyS_epoll_ctl",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781280,
      "name": "rb_insert_color_cached",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void rb_insert_color_cached(struct rb_node * node, struct rb_root_cached * root, bool leftmost)
```

```json
{
  "name": "rb_insert_color_cached",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589158720,
      "name": "rb_insert_color_cached",
      "external": true,
      "loc": "lib/rbtree.c:466",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "fs/eventpoll.c:ep_insert",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_service_tree_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589158720,
      "name": "rb_insert_color_cached",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void rb_insert_color_cached(struct rb_node * node, struct rb_root_cached * root, bool leftmost)
```

```json
{
  "name": "rb_insert_color_cached",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589388656,
      "name": "rb_insert_color_cached",
      "external": true,
      "loc": "lib/rbtree.c:466",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:__enqueue_entity",
        "kernel/sched/deadline.c:enqueue_task_dl",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue",
        "fs/eventpoll.c:ep_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589388656,
      "name": "rb_insert_color_cached",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579722585,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792974,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579866029,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125513,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033543,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765209,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579839598,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914653,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202729,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137351,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590087835,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579832396,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579869365,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579959184,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441585,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535637,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:__throtl_enqueue_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085771,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579827404,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862183,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947328,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582495453,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644357,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585234891,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579834110,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870759,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591653222,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:remove_waiter",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:task_blocks_on_rt_mutex",
        "kernel/locking/rtmutex.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527642,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584672597,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585117678,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579939388,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579980630,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:__enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592826070,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843675,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585090485,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585566398,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580052419,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580111108,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594733899,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402598,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585818085,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586719993,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580221798,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580284500,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596485643,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583987094,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586597763,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_service_queue_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595882537,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580282839,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351949,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597027184,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582126751,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_rbtree_add_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215997,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856035,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_service_queue_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596399945,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580406715,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:enqueue_dl_entity",
        "kernel/sched/build_policy.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597956528,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex_api.c:remove_waiter",
        "kernel/locking/rtmutex_api.c:try_to_take_rt_mutex",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain",
        "kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267682,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_rbtree_add_impl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584430541,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587133395,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_service_queue_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592087687,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "drivers/gpu/drm/drm_mm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mm.c:add_hole"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597295049,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:108",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490944560,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491028192,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491118124,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493766916,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495987800,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503865988,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224964708,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 3225035592,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3225119116,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 3227284188,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 3229328220,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236493836,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283803864,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283903904,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity",
        "kernel/sched/deadline.c:enqueue_pushable_dl_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284008732,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287378304,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290212760,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297725656,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271576442,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271632780,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271692930,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273367574,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275086102,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279761994,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579741065,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811950,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886765,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171465,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106087,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589690091,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579671449,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579746446,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579821741,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110905,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584041767,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589415883,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579725577,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799966,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579874925,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582161945,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584089847,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590133467,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
  "name": "rb_insert_color_cached",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579773113,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579844942,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:enqueue_dl_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579920445,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_enqueue_pi",
        "kernel/locking/rtmutex.c:rt_mutex_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238149,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192263,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590183851,
      "name": "rb_insert_color_cached",
      "external": false,
      "loc": "include/linux/rbtree.h:135",
      "file": "lib/timerqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/timerqueue.c:timerqueue_add"
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
void rb_insert_color_cached(struct rb_node * node, struct rb_root_cached * root, bool leftmost)
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
void rb_insert_color_cached(struct rb_node * node, struct rb_root_cached * root, bool leftmost)
```
</details>
</li>
</ul>
