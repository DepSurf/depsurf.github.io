# Function: <code>xen_event_channel_op_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844016,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xb_write",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844016,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584173616,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_comms.c:xb_write",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173616,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355008,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:set_affinity_irq",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_comms.c:xb_write",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355008,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436560,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436560,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584844960,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584844960,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585075808,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585075808,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int xen_event_channel_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_event_channel_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585185440,
      "name": "xen_event_channel_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:8",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu",
        "drivers/xen/events/events_base.c:xen_set_irq_priority",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq",
        "drivers/xen/events/events_base.c:__startup_pirq",
        "drivers/xen/events/events_base.c:notify_remote_via_irq",
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_unmask",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_setup",
        "drivers/xen/events/events_fifo.c:init_control_block",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_read",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/tty/hvc/hvc_xen.c:domU_write_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185440,
      "name": "xen_event_channel_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int xen_event_channel_op_compat(int cmd, void * arg)
```
</details>
</li>
</ul>
