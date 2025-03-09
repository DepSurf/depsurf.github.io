# Function: <code>__unbind_from_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860704,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:599",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860704,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584191264,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:610",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584191264,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372720,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:609",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372720,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454256,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:601",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454256,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864960,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:601",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864960,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096000,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:601",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096000,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585206784,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:601",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206784,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585419104,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:602",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419104,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559824,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:602",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559824,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586279984,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:616",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586279984,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397408,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:937",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397408,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281360,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:968",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281360,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794912,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:968",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794912,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588076112,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:968",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588076112,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1069
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458032,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:970",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458032,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1069
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:962",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589757520,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    },
    {
      "addr": 18446744071596758152,
      "name": "__unbind_from_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __unbind_from_irq(struct irq_info * info, unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:956",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:evtchn_put",
        "drivers/xen/events/events_base.c:unbind_from_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090960,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071597666600,
      "name": "__unbind_from_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498221816,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:602",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498221816,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585321536,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:606",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321536,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510224,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:602",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510224,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
void __unbind_from_irq(unsigned int irq)
```

```json
{
  "name": "__unbind_from_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618240,
      "name": "__unbind_from_irq",
      "external": false,
      "loc": "drivers/xen/events/events_base.c:602",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:unbind_from_irq",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618240,
      "name": "__unbind_from_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_info * info</code>
</li>
<li>
<b>Param reordered. </b>
<code>irq</code> ➡️ <code>info, irq</code>
</li>
</ul>
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
void __unbind_from_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __unbind_from_irq(unsigned int irq)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __unbind_from_irq(unsigned int irq)
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
void __unbind_from_irq(unsigned int irq)
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
