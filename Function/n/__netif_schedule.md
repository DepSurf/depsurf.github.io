# Function: <code>__netif_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287472,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2251",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/core/dev.c:netif_wake_subqueue",
        "net/core/dev.c:netif_tx_wake_queue",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287472,
      "name": "__netif_schedule",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715296,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2273",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_wake_subqueue",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715296,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901936,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2405",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_wake_subqueue",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901936,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587027184,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2439",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027184,
      "name": "__netif_schedule",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524464,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2466",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524464,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825104,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2510",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825104,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587958416,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2745",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_tx_wake_queue",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587958416,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588273824,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2755",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588273824,
      "name": "__netif_schedule",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588479440,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479440,
      "name": "__netif_schedule",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351840,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3033",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351840,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589357472,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3058",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589357472,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589257792,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3126",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257792,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589983456,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3047",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589983456,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591526242,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3082",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": [
        "net/core/dev.c:__dev_xmit_skb",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591481232,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593299594,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3067",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593249648,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593751539,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3097",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593710464,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594529811,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:3100",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:__dev_xmit_skb",
        "net/core/dev.c:netif_device_attach",
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594489440,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502010392,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502010392,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234743556,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234743556,
      "name": "__netif_schedule",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295421536,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295421536,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278286108,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netif_schedule_queue"
      ],
      "caller_func": [
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278286012,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588086224,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086224,
      "name": "__netif_schedule",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587783072,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587783072,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418000,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418000,
      "name": "__netif_schedule",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __netif_schedule(struct Qdisc * q)
```

```json
{
  "name": "__netif_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588556976,
      "name": "__netif_schedule",
      "external": true,
      "loc": "net/core/dev.c:2673",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_schedule_queue",
        "net/sched/sch_generic.c:__qdisc_run",
        "net/sched/sch_generic.c:sch_direct_xmit",
        "net/sched/sch_api.c:qdisc_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556976,
      "name": "__netif_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
