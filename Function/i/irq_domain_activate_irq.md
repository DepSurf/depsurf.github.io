# Function: <code>irq_domain_activate_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_domain_activate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768896,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1298",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/irqdomain.c:irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768896,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void irq_domain_activate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792096,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1356",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/hpet.c:hpet_resume",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/irqdomain.c:irq_domain_activate_irq",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792096,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void irq_domain_activate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819216,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1406",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819216,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void irq_domain_activate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817600,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1546",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:__irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817600,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852960,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1725",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852960,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886608,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1609",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886608,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933664,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1609",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933664,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972016,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1646",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972016,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021840,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021840,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072336,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1651",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:__irq_startup_managed",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072336,
      "name": "irq_domain_activate_irq",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054608,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1773",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:__irq_startup_managed",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054608,
      "name": "irq_domain_activate_irq",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055312,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1736",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055312,
      "name": "irq_domain_activate_irq",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187776,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1781",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187776,
      "name": "irq_domain_activate_irq",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336416,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1785",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336416,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580553296,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1853",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553296,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626608,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1834",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626608,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691664,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1834",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691664,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491225256,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491225256,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225239940,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225239940,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284104544,
      "name": "irq_domain_activate_irq",
      "external": false,
      "loc": "kernel/irq/internals.h:457",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271760968,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271760968,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990576,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990576,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579928352,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928352,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982112,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982112,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```

```json
{
  "name": "irq_domain_activate_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028752,
      "name": "irq_domain_activate_irq",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1649",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028752,
      "name": "irq_domain_activate_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reserve</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int irq_domain_activate_irq(struct irq_data * irq_data, bool reserve)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
