# Function: <code>bind_interdomain_evtchn_to_irqhandler_lateeoi</code>

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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(unsigned int remote_domain, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401648,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1449",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401648,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device * dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284416,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1486",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284416,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device * dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799120,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1492",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799120,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device * dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588080624,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1492",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080624,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device * dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589462608,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1494",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589462608,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device * dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589762528,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1487",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589762528,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(struct xenbus_device * dev, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098160,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1487",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098160,
      "name": "bind_interdomain_evtchn_to_irqhandler_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int bind_interdomain_evtchn_to_irqhandler_lateeoi(unsigned int remote_domain, evtchn_port_t remote_port, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
<li>
<b>Param removed. </b>
<code>unsigned int remote_domain</code>
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
