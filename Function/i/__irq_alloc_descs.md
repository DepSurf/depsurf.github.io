# Function: <code>__irq_alloc_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587335696,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:430",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587335696,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587834464,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:491",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587834464,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588049760,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:679",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588049760,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 660
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276912,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:696",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276912,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588842736,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:689",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588842736,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221936,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:706",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221936,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589464128,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:711",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589464128,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 577
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589924208,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589924208,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590150320,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590150320,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591168992,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:772",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591168992,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591664752,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:774",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_ipi_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591664752,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591608896,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:774",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608896,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592782128,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:786",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592782128,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594680272,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:763",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:__irq_domain_alloc_irqs",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594680272,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596416000,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:790",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596416000,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596955856,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:810",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/xen/events/events_base.c:bind_ipi_to_irqhandler",
        "drivers/xen/events/events_base.c:bind_virq_to_irq",
        "drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596955856,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597883376,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:810",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked",
        "kernel/irq/irqdomain.c:irq_domain_create_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irq_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode",
        "drivers/mfd/88pm860x-core.c:device_irq_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597883376,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503901960,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503901960,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236529576,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/tzic.c:tzic_init_dt",
        "arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler",
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/irqchip/irq-hip04.c:hip04_of_init",
        "drivers/irqchip/irq-omap-intc.c:omap_init_irq_legacy",
        "drivers/irqchip/irq-gic.c:gic_init_bases",
        "drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236529576,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284071984,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284071984,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279789980,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279789980,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589752608,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752608,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589476832,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "kernel/irq/irq_sim.c:irq_sim_init",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589476832,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590196016,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590196016,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590246448,
      "name": "__irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:766",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/devres.c:__devm_irq_alloc_descs",
        "kernel/irq/irqdomain.c:irq_create_strict_mappings",
        "kernel/irq/irqdomain.c:irq_create_direct_mapping",
        "kernel/irq/irqdomain.c:irq_domain_add_simple",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic",
        "drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/max8925-core.c:max8925_device_init",
        "drivers/mfd/tps6586x.c:tps6586x_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246448,
      "name": "__irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask * affinity</code>
</li>
</ul>
</details>
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
