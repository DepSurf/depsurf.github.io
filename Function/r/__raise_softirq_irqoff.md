# Function: <code>__raise_softirq_irqoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579390426,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:427",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "block/blk-iopoll.c:blk_iopoll_softirq",
        "block/blk-iopoll.c:blk_iopoll_sched",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:rps_trigger_softirq",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:dev_cpu_callback",
        "net/core/dev.c:net_rx_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393552,
      "name": "__raise_softirq_irqoff",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579404287,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:427",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:cpu_callback",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_callback",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405376,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579424605,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:441",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425680,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579412364,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:441",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413440,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439932,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:441",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:tasklet_hi_action",
        "kernel/softirq.c:tasklet_action",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441312,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454924,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:448",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456384,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488940,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490048,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506828,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507904,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532876,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533952,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562540,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:476",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564912,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544058,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:479",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546320,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549002,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:696",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_complete_request_remote",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550928,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:695",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule",
        "kernel/softirq.c:raise_softirq",
        "block/blk-mq.c:__blk_mq_complete_request_remote",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592100517,
      "name": "__raise_softirq_irqoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579621872,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:709",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "block/blk-mq.c:__blk_mq_complete_request_remote",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:trigger_rx_softirq",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593868087,
      "name": "__raise_softirq_irqoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579716080,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:709",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "block/blk-mq.c:__blk_mq_complete_request_remote",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:trigger_rx_softirq",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595973922,
      "name": "__raise_softirq_irqoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579842944,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:691",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "block/blk-mq.c:__blk_mq_complete_request_remote",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:trigger_rx_softirq",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596491538,
      "name": "__raise_softirq_irqoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579892944,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:691",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "block/blk-mq.c:__blk_mq_complete_request_remote",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_watchdog",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:trigger_rx_softirq",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597388299,
      "name": "__raise_softirq_irqoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579931632,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490676776,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/softirq.c:raise_softirq",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490676776,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224747852,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224747852,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283500400,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283500400,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271413562,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule_irqoff",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271413562,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506540,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507616,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435334,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436416,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506460,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507536,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __raise_softirq_irqoff(unsigned int nr)
```

```json
{
  "name": "__raise_softirq_irqoff",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539164,
      "name": "__raise_softirq_irqoff",
      "external": true,
      "loc": "kernel/softirq.c:449",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:takeover_tasklets",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq"
      ],
      "caller_func": [
        "lib/irq_poll.c:irq_poll_cpu_dead",
        "lib/irq_poll.c:irq_poll_softirq",
        "net/core/dev.c:dev_cpu_dead",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:rps_trigger_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540320,
      "name": "__raise_softirq_irqoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
