# Function: <code>irq_domain_free_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768448,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1230",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768448,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790848,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1286",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790848,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817968,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1312",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817968,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816400,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1456",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/kernel/apic/htirq.c:arch_teardown_ht_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816400,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851760,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1626",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851760,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885472,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1510",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885472,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932528,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1510",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932528,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970912,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1547",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970912,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020720,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020720,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071232,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1552",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_alloc_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071232,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053520,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1674",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "drivers/iommu/amd/init.c:iommu_setup_intcapxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053520,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053856,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1641",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053856,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186304,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1686",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs",
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186304,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580334848,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1690",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334848,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580552432,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1758",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552432,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625792,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1736",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625792,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690848,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1736",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "drivers/iommu/amd/init.c:__iommu_setup_intcapxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690848,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491223824,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491223824,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225238460,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs",
        "drivers/irqchip/irq-gic-v4.c:its_free_vcpu_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225238460,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_domain_free_irqs",
      "external": false,
      "loc": "include/linux/irqdomain.h:546",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271759850,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271759850,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989456,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989456,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927232,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927232,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980992,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980992,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
```

```json
{
  "name": "irq_domain_free_irqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027632,
      "name": "irq_domain_free_irqs",
      "external": true,
      "loc": "kernel/irq/irqdomain.c:1550",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_unmap_irq",
        "arch/x86/kernel/apic/msi.c:dmar_free_hwirq",
        "arch/x86/kernel/apic/msi.c:native_teardown_msi_irq",
        "arch/x86/platform/uv/uv_irq.c:uv_teardown_irq",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/irqdomain.c:irq_create_fwspec_mapping",
        "kernel/irq/msi.c:msi_domain_free_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027632,
      "name": "irq_domain_free_irqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void irq_domain_free_irqs(unsigned int virq, unsigned int nr_irqs)
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
