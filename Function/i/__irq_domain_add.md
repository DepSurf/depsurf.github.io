# Function: <code>__irq_domain_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765520,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:96",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765520,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788176,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:94",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788176,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815296,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:94",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815296,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813408,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:125",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813408,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848304,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:127",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848304,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:129",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886823,
      "name": "__irq_domain_add.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579882064,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:129",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933879,
      "name": "__irq_domain_add.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579929840,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:129",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972476,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579968208,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022058,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580018016,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072490,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580064944,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:139",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304144,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580046960,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:139",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591246920,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580047680,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:139",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592139897,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580180688,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:139",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593910632,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580328832,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548574,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:248",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_simple"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545312,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580621550,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:255",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_simple"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618752,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580686494,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:255",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_create_simple"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "kernel/irq/irq_sim.c:irq_domain_create_sim",
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683648,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491220184,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_probe_one",
        "drivers/irqchip/irq-partition-percpu.c:partition_create_desc",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init",
        "drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe",
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe",
        "drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe",
        "drivers/irqchip/qcom-irq-combiner.c:combiner_probe",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pci-aardvark.c:advk_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe",
        "drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe",
        "drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe",
        "drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/edac/altera_edac.c:altr_edac_a10_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491220184,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225235280,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-alpine-msi.c:alpine_msix_init",
        "drivers/irqchip/exynos-combiner.c:combiner_init",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_init",
        "drivers/irqchip/irq-orion.c:orion_irq_init",
        "drivers/irqchip/irq-omap-intc.c:intc_of_init",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/irqchip/irq-partition-percpu.c:partition_create_desc",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-rda-intc.c:rda8810_intc_init",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_probe",
        "drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init",
        "drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_probe",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
        "drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-altera.c:altera_pcie_probe",
        "drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq",
        "drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe",
        "drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init",
        "drivers/soc/dove/pmu.c:dove_init_pmu_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/memory/omap-gpmc.c:gpmc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225235280,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284122400,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/mpic.c:mpic_alloc",
        "arch/powerpc/sysdev/xics/xics-common.c:xics_init",
        "arch/powerpc/sysdev/xive/common.c:xive_core_init",
        "arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284122400,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271757022,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/irqchip/irq-al-fic.c:al_fic_init_dt",
        "drivers/irqchip/irq-sifive-plic.c:plic_init",
        "drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271757022,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990794,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579986752,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579928570,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579924528,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982330,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579978288,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct irq_domain * __irq_domain_add(struct fwnode_handle * fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops * ops, void * host_data)
```

```json
{
  "name": "__irq_domain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_domain_add",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/vector.c:arch_early_irq_init",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_create_hierarchy",
        "kernel/irq/irqdomain.c:irq_domain_add_legacy",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/arizona-irq.c:arizona_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_init",
        "drivers/mfd/max8997-irq.c:max8997_irq_init",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028970,
      "name": "__irq_domain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580024928,
      "name": "__irq_domain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
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
