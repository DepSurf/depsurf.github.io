# Function: <code>xen_physdev_op_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844208,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_set_iopl_mask",
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844208,
      "name": "xen_physdev_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584173808,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_set_iopl_mask",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173808,
      "name": "xen_physdev_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584355200,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_set_iopl_mask",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355200,
      "name": "xen_physdev_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436720,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436720,
      "name": "xen_physdev_op_compat",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845136,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845136,
      "name": "xen_physdev_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585075984,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/pci.c:xen_mcfg_late",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585075984,
      "name": "xen_physdev_op_compat",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int xen_physdev_op_compat(int cmd, void * arg)
```

```json
{
  "name": "xen_physdev_op_compat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585185616,
      "name": "xen_physdev_op_compat",
      "external": true,
      "loc": "drivers/xen/fallback.c:47",
      "file": "drivers/xen/fallback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask",
        "drivers/xen/events/events_base.c:xen_init_IRQ",
        "drivers/xen/events/events_base.c:xen_irq_resume",
        "drivers/xen/events/events_base.c:xen_test_irq_shared",
        "drivers/xen/events/events_base.c:xen_destroy_irq",
        "drivers/xen/events/events_base.c:xen_allocate_pirq_msi",
        "drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq",
        "drivers/xen/events/events_base.c:eoi_pirq",
        "drivers/xen/events/events_base.c:pirq_query_unmask",
        "drivers/xen/pci.c:xen_mcfg_late",
        "drivers/xen/dbgp.c:xen_dbgp_op",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:acpi_register_gsi_xen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585185616,
      "name": "xen_physdev_op_compat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int xen_physdev_op_compat(int cmd, void * arg)
```
</details>
</li>
</ul>
