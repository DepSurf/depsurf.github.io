# Function: <code>bind_evtchn_to_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861440,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1021",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861440,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192000,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1032",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192000,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373456,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1031",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373456,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454960,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1023",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454960,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865664,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1023",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865664,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096672,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1021",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096672,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207424,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1021",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207424,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585419840,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1022",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419840,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560544,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1022",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560544,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281728,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1037",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront_split",
        "drivers/net/xen-netfront.c:setup_netfront_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281728,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401968,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1406",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront_split",
        "drivers/net/xen-netfront.c:setup_netfront_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401968,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284624,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1444",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:setup_blkring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284624,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798976,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1450",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798976,
      "name": "bind_evtchn_to_irqhandler",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588080880,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1450",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588080880,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589462416,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1452",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589462416,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589762336,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1445",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589762336,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590099632,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1445",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590099632,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498222584,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1022",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498222584,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585322256,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1026",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322256,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510944,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1022",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510944,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_evtchn_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618960,
      "name": "bind_evtchn_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1022",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618960,
      "name": "bind_evtchn_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<b>Param type changed. </b>
<code>unsigned int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
