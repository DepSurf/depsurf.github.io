# Function: <code>irq_domain_free_irqs_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579766832,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1082",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579766832,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788000,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1133",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788000,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815120,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1159",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815120,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812048,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1328",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812048,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579846064,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1328",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846064,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879872,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1212",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879872,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927152,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1212",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927152,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965584,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1249",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965584,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015360,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015360,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067632,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1253",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067632,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050144,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1359",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050144,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050176,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1326",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050176,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182000,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1366",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182000,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330256,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1369",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330256,
      "name": "irq_domain_free_irqs_common",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546320,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1429",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546320,
      "name": "irq_domain_free_irqs_common",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621344,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1408",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621344,
      "name": "irq_domain_free_irqs_common",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686288,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1408",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd/iommu.c:irq_remapping_free",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc",
        "drivers/base/platform-msi.c:platform_msi_device_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686288,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491217032,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491217032,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225232352,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225232352,
      "name": "irq_domain_free_irqs_common",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271754426,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271754426,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984096,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984096,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921872,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921872,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975632,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975632,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022256,
      "name": "irq_domain_free_irqs_common",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1251",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs_top",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "drivers/iommu/amd_iommu.c:irq_remapping_free",
        "drivers/iommu/amd_iommu.c:irq_remapping_alloc",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_free",
        "drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc",
        "drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_free",
        "drivers/base/platform-msi.c:platform_msi_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022256,
      "name": "irq_domain_free_irqs_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void irq_domain_free_irqs_common(struct irq_domain * domain, unsigned int virq, unsigned int nr_irqs)
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
