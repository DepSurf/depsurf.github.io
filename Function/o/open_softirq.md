# Function: <code>open_softirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579393664,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:433",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "block/blk-softirq.c:blk_softirq_init",
        "block/blk-iopoll.c:blk_iopoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393664,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595247567,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:433",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405488,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595491732,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:447",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425792,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596412844,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:447",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413552,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602737571,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:447",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441424,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602910022,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:454",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456496,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604707630,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490160,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604807971,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508016,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604842284,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534064,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609176664,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:482",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565024,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612242098,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:486",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546416,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614382604,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:703",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551024,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615315606,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:702",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623568,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617097412,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:716",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717792,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627758208,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:716",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579844864,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619518800,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:698",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895088,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621815808,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:698",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-mq.c:blk_mq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933776,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510874860,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490678248,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243361528,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224749056,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302504888,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283502048,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270617114,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414454,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604747551,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507728,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604715168,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436528,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604825118,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507648,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void open_softirq(int nr, void (*)(struct softirq_action *) action)
```

```json
{
  "name": "open_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604846441,
      "name": "open_softirq",
      "external": true,
      "loc": "kernel/softirq.c:455",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:softirq_init",
        "kernel/softirq.c:softirq_init"
      ],
      "caller_func": [
        "kernel/sched/fair.c:init_sched_fair_class",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/time/timer.c:init_timers",
        "kernel/time/hrtimer.c:hrtimers_init",
        "block/blk-softirq.c:blk_softirq_init",
        "lib/irq_poll.c:irq_poll_setup",
        "net/core/dev.c:net_dev_init",
        "net/core/dev.c:net_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540448,
      "name": "open_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
