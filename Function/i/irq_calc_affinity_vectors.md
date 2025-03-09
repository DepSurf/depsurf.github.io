# Function: <code>irq_calc_affinity_vectors</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int irq_calc_affinity_vectors(int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827664,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:144",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827664,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827584,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:206",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827584,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863344,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:207",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863344,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897520,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:257",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897520,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int irq_calc_affinity_vectors(int minvec, int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944832,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:307",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944832,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579983536,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:325",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983536,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580033680,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033680,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084400,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084400,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066976,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066976,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067616,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067616,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580201168,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580201168,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580354384,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:497",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354384,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576736,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:497",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576736,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580649296,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:110",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649296,
      "name": "irq_calc_affinity_vectors",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580714512,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:110",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580714512,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491238552,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491238552,
      "name": "irq_calc_affinity_vectors",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225251336,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225251336,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284139232,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284139232,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271768378,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271768378,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002416,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002416,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941088,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941088,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993952,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993952,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
unsigned int irq_calc_affinity_vectors(unsigned int minvec, unsigned int maxvec, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_calc_affinity_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040688,
      "name": "irq_calc_affinity_vectors",
      "external": true,
      "loc": "kernel/irq/affinity.c:496",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040688,
      "name": "irq_calc_affinity_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int irq_calc_affinity_vectors(int maxvec, const struct irq_affinity * affd)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int minvec</code>
</li>
<li>
<b>Param reordered. </b>
<code>maxvec, affd</code> ➡️ <code>minvec, maxvec, affd</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int minvec</code> ➡️ <code>unsigned int minvec</code>
</li>
<li>
<b>Param type changed. </b>
<code>int maxvec</code> ➡️ <code>unsigned int maxvec</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
