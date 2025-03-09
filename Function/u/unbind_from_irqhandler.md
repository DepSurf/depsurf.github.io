# Function: <code>unbind_from_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861696,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1106",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861696,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192224,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1117",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192224,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584373680,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1116",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:xennet_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584373680,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455184,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1108",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455184,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865888,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1108",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865888,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096896,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1106",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096896,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585207648,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1106",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585207648,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1107",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424497,
      "name": "unbind_from_irqhandler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585420064,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560768,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1107",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560768,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281600,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1122",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront_split",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281600,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397920,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1504",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront_split",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397920,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281888,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1541",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281888,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586795920,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1547",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795920,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077184,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1547",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077184,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459120,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1549",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459120,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589758640,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1542",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589758640,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590095840,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1542",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590095840,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498222912,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1107",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498222912,
      "name": "unbind_from_irqhandler",
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585322480,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1111",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322480,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585511168,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1107",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511168,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```

```json
{
  "name": "unbind_from_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619184,
      "name": "unbind_from_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1107",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_teardown_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp.c:xen_smp_intr_free",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_free_pv",
        "arch/x86/xen/spinlock.c:xen_uninit_lock_cpu",
        "drivers/xen/xenbus/xenbus_comms.c:xb_deinit_comms",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvc_init",
        "drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend",
        "drivers/block/xen-blkfront.c:blkif_free_ring",
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619184,
      "name": "unbind_from_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
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
void unbind_from_irqhandler(unsigned int irq, void * dev_id)
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
