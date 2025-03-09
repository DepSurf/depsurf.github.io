# Function: <code>bind_virq_to_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864096,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1064",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864096,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194608,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1075",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194608,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584376096,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1074",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376096,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457552,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1066",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457552,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868240,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1066",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868240,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585099200,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1064",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099200,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585209936,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1064",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209936,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422240,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1065",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422240,
      "name": "bind_virq_to_irqhandler",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585562928,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1065",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562928,
      "name": "bind_virq_to_irqhandler",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586284512,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1080",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284512,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404736,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1462",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404736,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287488,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1499",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287488,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802704,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1505",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802704,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588084640,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1505",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588084640,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589466880,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1507",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589466880,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589766800,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1500",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589766800,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590103232,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1500",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590103232,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498225472,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1065",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498225472,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324640,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1069",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324640,
      "name": "bind_virq_to_irqhandler",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585513328,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1065",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513328,
      "name": "bind_virq_to_irqhandler",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```

```json
{
  "name": "bind_virq_to_irqhandler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585621344,
      "name": "bind_virq_to_irqhandler",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:1065",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_timer",
        "arch/x86/xen/smp.c:xen_smp_intr_init",
        "arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv",
        "drivers/xen/pcpu.c:xen_pcpu_init",
        "drivers/xen/mcelog.c:bind_virq_for_mce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621344,
      "name": "bind_virq_to_irqhandler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char * devname, void * dev_id)
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
