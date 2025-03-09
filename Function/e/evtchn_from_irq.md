# Function: <code>evtchn_from_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583858912,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858912,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189312,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189312,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584370800,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:247",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370800,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584452528,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:247",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452528,
      "name": "evtchn_from_irq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584863120,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:247",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863120,
      "name": "evtchn_from_irq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094208,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:247",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094208,
      "name": "evtchn_from_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204992,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:247",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204992,
      "name": "evtchn_from_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417088,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417088,
      "name": "evtchn_from_irq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557808,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557808,
      "name": "evtchn_from_irq",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586285580,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:262",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:disable_pirq",
        "drivers/xen/events/events_base.c:enable_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:mask_ack_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:mask_ack_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278272,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586406012,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:388",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402192,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586289324,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:405",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284960,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586805181,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:405",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799664,
      "name": "evtchn_from_irq",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588087293,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:405",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588081296,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589469677,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:406",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463344,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
evtchn_port_t evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589769597,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:407",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:shutdown_pirq",
        "drivers/xen/events/events_base.c:__startup_pirq"
      ],
      "caller_func": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589763264,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590105677,
      "name": "evtchn_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:410",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_poll_irq",
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_base.c:irq_evtchn_from_virq"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498219424,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498219424,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319520,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:252",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319520,
      "name": "evtchn_from_irq",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585508208,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508208,
      "name": "evtchn_from_irq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```

```json
{
  "name": "evtchn_from_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616224,
      "name": "evtchn_from_irq",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:248",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_test_irq_pending",
        "drivers/xen/events/events_base.c:xen_set_irq_pending",
        "drivers/xen/events/events_base.c:xen_clear_irq_pending",
        "drivers/xen/events/events_base.c:retrigger_dynirq",
        "drivers/xen/events/events_base.c:ack_dynirq",
        "drivers/xen/events/events_base.c:disable_dynirq",
        "drivers/xen/events/events_base.c:enable_dynirq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_send_IPI_one",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:__unbind_from_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616224,
      "name": "evtchn_from_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>evtchn_port_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
evtchn_port_t evtchn_from_irq(unsigned int irq)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
unsigned int evtchn_from_irq(unsigned int irq)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
