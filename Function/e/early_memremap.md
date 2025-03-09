# Function: <code>early_memremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595155611,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:216",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_e820_ext",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/firmware/efi/efi.c:efi_mem_desc_lookup",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595155611,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595329158,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:216",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_e820_ext",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_desc_lookup",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595329158,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595577336,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:216",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_e820_ext",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595577336,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:216",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596504966,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602832391,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602832391,
      "name": "early_memremap",
      "section": ".init.text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603005711,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603005711,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604804339,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604804339,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907739,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907739,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604941585,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604941585,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609255421,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609255421,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612321730,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612321730,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614461942,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614461942,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615407457,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:219",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615407457,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617199608,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:220",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617199608,
      "name": "early_memremap",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627899602,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:220",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627899248,
      "name": "early_memremap",
      "section": ".init.text",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619662658,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:218",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619662304,
      "name": "early_memremap",
      "section": ".init.text",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621968706,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:218",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621968352,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510982004,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi.c:__acpi_map_table",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510982004,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243461288,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243461288,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604847045,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604847045,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604816097,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604816097,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604924229,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604924229,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "early_memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604945756,
      "name": "early_memremap",
      "external": true,
      "loc": "mm/early_ioremap.c:224",
      "file": "mm/early_ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_map_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "mm/early_ioremap.c:copy_from_early_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_setup",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604945756,
      "name": "early_memremap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * early_memremap(resource_size_t phys_addr, long unsigned int size)
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
