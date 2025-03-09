# Function: <code>alloc_msi_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774496,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:21",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774496,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct msi_desc * alloc_msi_entry(struct device * dev)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797696,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:21",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797696,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct cpumask * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824880,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824880,
      "name": "alloc_msi_entry",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct cpumask * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579824384,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824384,
      "name": "alloc_msi_entry",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct cpumask * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859952,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:31",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859952,
      "name": "alloc_msi_entry",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct cpumask * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893728,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:30",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893728,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940768,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940768,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979408,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979408,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029056,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029056,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079712,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079712,
      "name": "alloc_msi_entry",
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062064,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062064,
      "name": "alloc_msi_entry",
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062800,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_capability_init",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062800,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195600,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:32",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195600,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491233840,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_msi_domain_alloc_irqs",
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/soc/ti/ti_sci_inta_msi.c:ti_sci_inta_msi_domain_alloc_irqs",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491233840,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225247312,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:__pci_enable_msi_range",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225247312,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284135200,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284135200,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271765190,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271765190,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579997792,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579997792,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936464,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936464,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989328,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989328,
      "name": "alloc_msi_entry",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "alloc_msi_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036064,
      "name": "alloc_msi_entry",
      "external": true,
      "loc": "kernel/irq/msi.c:29",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi.c:msi_setup_entry",
        "drivers/base/platform-msi.c:platform_msi_alloc_descs_with_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036064,
      "name": "alloc_msi_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nvec</code>
</li>
<li>
<b>Param added. </b>
<code>const struct cpumask * affinity</code>
</li>
</ul>
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
<b>Param type changed. </b>
<code>const struct cpumask * affinity</code> ➡️ <code>const struct irq_affinity_desc * affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct msi_desc * alloc_msi_entry(struct device * dev, int nvec, const struct irq_affinity_desc * affinity)
```
</details>
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
