# Function: <code>irq_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579247314,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:240",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_resume",
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579770128,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:240",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579879467,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:240",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880874,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:240",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864983,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:240",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579247517,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:251",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793328,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:251",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579908987,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:251",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579910415,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:251",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584195531,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:251",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259917,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:263",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work",
        "arch/x86/kernel/hpet.c:hpet_msi_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820411,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:263",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579939436,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:263",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940880,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:263",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584377019,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:263",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579255612,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579818543,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579947356,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579948800,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584458455,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579272380,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:274",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853919,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:274",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579993052,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:274",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994512,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:274",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584869143,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:274",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579283469,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579887483,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580045146,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580046631,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100103,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:272",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307421,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:286",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579934539,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:286",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580091994,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:286",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580093463,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:286",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585210855,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:286",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579323669,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:313",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579973183,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:313",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580135849,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:313",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580137335,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:313",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585423204,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:313",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579327717,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022707,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580183993,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580185479,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585563876,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357386,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:329",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580073196,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:329",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580249210,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:329",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250628,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:329",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586285209,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:329",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357162,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:330",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580055307,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:330",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580233114,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:330",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234452,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:330",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447652,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:330",
      "file": "drivers/xen/platform-pci.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579361733,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:334",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056010,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:334",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580237962,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:334",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239572,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:334",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586331508,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:334",
      "file": "drivers/xen/platform-pci.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask * cpumask)
```

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156544,
      "name": "irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:466",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156544,
      "name": "irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int irq_set_affinity(unsigned int irq, const struct cpumask * cpumask)
```

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580302288,
      "name": "irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:481",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302288,
      "name": "irq_set_affinity",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask * cpumask)
```

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514496,
      "name": "irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:473",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514496,
      "name": "irq_set_affinity",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask * cpumask)
```

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587392,
      "name": "irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:476",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587392,
      "name": "irq_set_affinity",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask * cpumask)
```

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651744,
      "name": "irq_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:478",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "kernel/time/tick-common.c:tick_setup_device",
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651744,
      "name": "irq_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490552236,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "virt/kvm/arm/vgic/vgic-v4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_flush_hwstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491226248,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491408320,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491410592,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496428312,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/irqchip/irq-ls-scfg-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497125288,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/pci/controller/pci-xgene-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497128124,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/pci/controller/pcie-iproc-msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498089396,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/soc/fsl/qbman/bman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman_portal.c:bman_online_cpu",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498090820,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/soc/fsl/qbman/qman_portal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman_portal.c:qman_online_cpu",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_offline_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498094432,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/bman.c:bman_create_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498109220,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_create_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498226432,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501783548,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu",
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795876,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501806720,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225240692,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225404476,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_setup_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3225406688,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282927356,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "arch/powerpc/sysdev/xics/xics-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xics/xics-common.c:xics_migrate_irqs_away"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284128144,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284354688,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284358248,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271762054,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271885336,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579323621,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991443,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580153193,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580154279,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585325588,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579258133,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579930115,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580098744,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580100391,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579323541,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579982979,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580144265,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580145751,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514276,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
  "name": "irq_set_affinity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579331829,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580029619,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/irq/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580196217,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580197735,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_set_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585622292,
      "name": "irq_set_affinity",
      "external": false,
      "loc": "include/linux/interrupt.h:314",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:rebind_evtchn_irq"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int irq_set_affinity(unsigned int irq, const struct cpumask * cpumask)
```
</details>
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
