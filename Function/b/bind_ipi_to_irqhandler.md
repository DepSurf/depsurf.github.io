# Function: <code>bind_ipi_to_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864224,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1083",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864224,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194736,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1094",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194736,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376224,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1093",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376224,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457680,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1085",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457680,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868368,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1085",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868368,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585099328,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1083",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099328,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210064,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1083",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210064,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1084",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585424612,
      "name": "bind_ipi_to_irqhandler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585422368,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585563056,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1084",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563056,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284656,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1099",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284656,
      "name": "bind_ipi_to_irqhandler",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404880,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1481",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404880,
      "name": "bind_ipi_to_irqhandler",
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287632,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1518",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287632,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802848,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1524",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802848,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588084816,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1524",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084816,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589467072,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1526",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589467072,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589766992,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1519",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589766992,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590103488,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1519",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590103488,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1049
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498225640,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1084",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498225640,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324768,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1088",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324768,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513456,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1084",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513456,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_ipi_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585621472,
      "name": "bind_ipi_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1084",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621472,
      "name": "bind_ipi_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
