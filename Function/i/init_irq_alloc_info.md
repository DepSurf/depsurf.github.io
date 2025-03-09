# Function: <code>init_irq_alloc_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195232,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:288",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195232,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579195872,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:290",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195872,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207552,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:290",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207552,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579205472,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:297",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579205472,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579223232,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:64",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579223232,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235472,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:65",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235472,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259152,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:66",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259152,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273216,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273216,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275632,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275632,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304272,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304272,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309440,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:iommu_setup_intcapxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309440,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312256,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312256,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579361072,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579361072,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424032,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424032,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507632,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:pci_msi_prepare",
        "arch/x86/kernel/apic/msi.c:x86_msi_prepare",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507632,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519888,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:pci_msi_prepare",
        "arch/x86/kernel/apic/msi.c:x86_msi_prepare",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519888,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548640,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:74",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:pci_msi_prepare",
        "arch/x86/kernel/apic/msi.c:x86_msi_prepare",
        "arch/x86/kernel/hpet.c:hpet_select_clockevents",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq",
        "drivers/iommu/amd/init.c:__iommu_setup_intcapxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548640,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274336,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274336,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579209680,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209680,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275536,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275536,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```

```json
{
  "name": "init_irq_alloc_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579281440,
      "name": "init_irq_alloc_info",
      "external": true,
      "loc": "arch/x86/kernel/apic/vector.c:63",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/msi.c:hpet_assign_irq",
        "arch/x86/kernel/apic/msi.c:hpet_create_irq_domain",
        "arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq",
        "arch/x86/kernel/apic/msi.c:native_setup_msi_irqs",
        "arch/x86/platform/uv/uv_irq.c:uv_setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281440,
      "name": "init_irq_alloc_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info * info, const struct cpumask * mask)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
