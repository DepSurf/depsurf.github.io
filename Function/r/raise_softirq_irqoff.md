# Function: <code>raise_softirq_irqoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579391143,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:401",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "block/blk-softirq.c:trigger_softirq",
        "block/blk-softirq.c:__blk_complete_request",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:dev_cpu_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393200,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579404287,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:401",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_callback",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405056,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579424605,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:415",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425360,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579412364,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:415",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413120,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439932,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:415",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440976,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454924,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:422",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456032,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488940,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489696,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506828,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507552,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532876,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533600,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562540,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:450",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564576,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544058,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:453",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-mq.c:blk_softirq_cpu_dead",
        "block/blk-mq.c:blk_mq_trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546032,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549002,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:670",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550624,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579622953,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:669",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621968,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717175,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:683",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_reschedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716208,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579844231,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:683",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "lib/irq_poll.c:irq_poll_sched",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_reschedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843088,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894455,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:665",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "lib/irq_poll.c:irq_poll_sched",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:dev_kfree_skb_irq_reason",
        "net/core/dev.c:__netif_reschedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893088,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933143,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:665",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:nohz_csd_func",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "lib/irq_poll.c:irq_poll_sched",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:dev_kfree_skb_irq_reason",
        "net/core/dev.c:__netif_reschedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931776,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490678060,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490676968,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224748836,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224748032,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283501792,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283500656,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271414276,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_reschedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271413726,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506540,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507264,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435334,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436096,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506460,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507184,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539164,
      "name": "raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:423",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/rcu/tree.c:__rcu_read_unlock",
        "kernel/time/hrtimer.c:hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:blk_softirq_cpu_dead",
        "block/blk-softirq.c:trigger_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539936,
      "name": "raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
