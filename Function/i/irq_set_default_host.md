# Function: <code>irq_set_default_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579763216,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:295",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763216,
      "name": "irq_set_default_host",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786240,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:291",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786240,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813360,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:314",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813360,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811632,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:450",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811632,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845648,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:451",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845648,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879424,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:453",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879424,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926704,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:453",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926704,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965168,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:453",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965168,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014928,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014928,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580069273,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:440",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064560,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051785,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:461",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046304,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051840,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:463",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047168,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580184445,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:473",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180080,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580332925,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:473",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328064,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580549456,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:497",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543728,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580622864,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:479",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617184,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687808,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:479",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682080,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491216416,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_remove",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491216416,
      "name": "irq_set_default_host",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225232084,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": [
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225231756,
      "name": "irq_set_default_host",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284119680,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_alloc",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_init",
        "arch/powerpc/sysdev/xive/common.c:xive_core_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284119680,
      "name": "irq_set_default_host",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271754154,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271753868,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983664,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983664,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921440,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921440,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975200,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975200,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void irq_set_default_host(struct irq_domain * domain)
```

```json
{
  "name": "irq_set_default_host",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580021824,
      "name": "irq_set_default_host",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:455",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irqdomain.c:irq_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580021824,
      "name": "irq_set_default_host",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
