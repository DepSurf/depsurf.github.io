# Function: <code>irq_create_affinity_masks</code>

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
struct cpumask * irq_create_affinity_masks(int nvecs, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826320,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:60",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826320,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1329
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
struct cpumask * irq_create_affinity_masks(int nvecs, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579825872,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:104",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579825872,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1705
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
struct cpumask * irq_create_affinity_masks(int nvecs, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861696,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:105",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861696,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1640
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
struct cpumask * irq_create_affinity_masks(int nvecs, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896576,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:177",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896576,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
struct irq_affinity_desc * irq_create_affinity_masks(int nvecs, const struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943600,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:235",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943600,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:245",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579983624,
      "name": "irq_create_affinity_masks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579982400,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1134
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032592,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032592,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083808,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083808,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066384,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066384,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067024,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067024,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580200544,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200544,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580353744,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:417",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:__pci_enable_msi_range",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353744,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576080,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:417",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576080,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:26",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596507762,
      "name": "irq_create_affinity_masks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071580648240,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:26",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:msi_capability_init",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity",
        "drivers/base/platform.c:devm_platform_get_irqs_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597405427,
      "name": "irq_create_affinity_masks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071580713456,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1039
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491237512,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491237512,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225250400,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
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
      "addr": 3225250400,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 936
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284138384,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284138384,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271767682,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271767682,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001328,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001328,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940000,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940000,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992864,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992864,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
struct irq_affinity_desc * irq_create_affinity_masks(unsigned int nvecs, struct irq_affinity * affd)
```

```json
{
  "name": "irq_create_affinity_masks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039600,
      "name": "irq_create_affinity_masks",
      "external": true,
      "loc": "kernel/irq/affinity.c:416",
      "file": "kernel/irq/affinity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:pci_alloc_irq_vectors_affinity",
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039600,
      "name": "irq_create_affinity_masks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
struct cpumask * irq_create_affinity_masks(int nvecs, const struct irq_affinity * affd)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct cpumask *</code> ➡️ <code>struct irq_affinity_desc *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nvecs</code> ➡️ <code>unsigned int nvecs</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity * affd</code> ➡️ <code>struct irq_affinity * affd</code>
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
