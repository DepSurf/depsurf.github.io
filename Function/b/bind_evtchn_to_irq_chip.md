# Function: <code>bind_evtchn_to_irq_chip</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401136,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1165",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401136,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip, struct xenbus_device * dev)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586283872,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1202",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586283872,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip, struct xenbus_device * dev)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798480,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1202",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798480,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip, struct xenbus_device * dev)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588079920,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1202",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079920,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip, struct xenbus_device * dev)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589461840,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1204",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589461840,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip, struct xenbus_device * dev)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589761760,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1197",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589761760,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip, struct xenbus_device * dev)
```

```json
{
  "name": "bind_evtchn_to_irq_chip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590097728,
      "name": "bind_evtchn_to_irq_chip",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:1192",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097728,
      "name": "bind_evtchn_to_irq_chip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int bind_evtchn_to_irq_chip(evtchn_port_t evtchn, struct irq_chip * chip)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xenbus_device * dev</code>
</li>
</ul>
</details>
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
