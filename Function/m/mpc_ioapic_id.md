# Function: <code>mpc_ioapic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595042759,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:123",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200848,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579205478,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:123",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201472,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217142,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213168,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579214537,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:122",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210720,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579232190,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:123",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228368,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579247013,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:124",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241008,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270810,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:124",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264784,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579285067,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278720,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579287471,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281184,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316957,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC_irqs",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:check_ioapic_information",
        "drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310800,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591261221,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC_irqs",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:check_ioapic_information",
        "drivers/iommu/intel/irq_remapping.c:parse_ioapics_under_ir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316096,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591204301,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318864,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373136,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373232,
      "name": "mpc_ioapic_id",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435215,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:126",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437120,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520904,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:126",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521856,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533422,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:127",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534384,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562237,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:127",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:IO_APIC_get_PCI_irq_vector",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:mp_config_acpi_legacy_irqs",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd/init.c:early_amd_iommu_init",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563200,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579286175,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279888,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221458,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215216,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579287375,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281088,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```

```json
{
  "name": "mpc_ioapic_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293263,
      "name": "mpc_ioapic_id",
      "external": true,
      "loc": "arch/x86/kernel/apic/io_apic.c:125",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:acpi_get_override_irq",
        "arch/x86/kernel/apic/io_apic.c:ioapic_resume",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:setup_IO_APIC",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:print_IO_APICs",
        "arch/x86/kernel/apic/io_apic.c:mp_map_gsi_to_irq",
        "arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq",
        "arch/x86/kernel/apic/io_apic.c:find_isa_irq_apic",
        "arch/x86/kernel/apic/io_apic.c:clear_IO_APIC_pin"
      ],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_boot_init",
        "arch/x86/kernel/acpi/boot.c:acpi_register_gsi_ioapic",
        "arch/x86/kernel/acpi/boot.c:mp_register_ioapic_irq",
        "arch/x86/kernel/mpparse.c:construct_default_ioirq_mptable",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286976,
      "name": "mpc_ioapic_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int mpc_ioapic_id(int ioapic_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mpc_ioapic_id(int ioapic_idx)
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
