# Function: <code>early_memunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595155760,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:277",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:parse_e820_ext",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_unmap_memmap",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/firmware/efi/efi.c:efi_mem_desc_lookup",
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
      "addr": 18446744071595155792,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595329307,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:277",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_read_phys_ulong",
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
        "arch/x86/platform/efi/efi.c:efi_unmap_memmap",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_desc_lookup",
        "drivers/firmware/efi/efi.c:efi_mem_desc_lookup",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595329339,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595577485,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:277",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_read_phys_ulong",
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
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595577517,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596505109,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:277",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
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
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_config_init",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596505141,
      "name": "early_memunmap",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602832626,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602832658,
      "name": "early_memunmap",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603005967,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603005992,
      "name": "early_memunmap",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604804595,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604804620,
      "name": "early_memunmap",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604908000,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908025,
      "name": "early_memunmap",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604941846,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604941871,
      "name": "early_memunmap",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609255682,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609255707,
      "name": "early_memunmap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612321991,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612322016,
      "name": "early_memunmap",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614462199,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614462225,
      "name": "early_memunmap",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615407714,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:295",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615407740,
      "name": "early_memunmap",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617199891,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:296",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
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
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617199931,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627899652,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:296",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
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
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627899744,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619662708,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:294",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
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
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619662800,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621968756,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:294",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/setup.c:xen_phys_memcpy",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/sev.c:get_secrets_page",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "arch/x86/platform/efi/efi.c:efi_systab_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init",
        "drivers/firmware/efi/efi.c:efi_systab_report_header",
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
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/tpm.c:tpm2_calc_event_log_size",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621968848,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510982416,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/arm64/kernel/acpi.c:__acpi_unmap_table",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/arm-init.c:efi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510982456,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243461544,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/arm-init.c:efi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init",
        "drivers/firmware/efi/arm-init.c:uefi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243461572,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604847306,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604847331,
      "name": "early_memunmap",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604816358,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604816383,
      "name": "early_memunmap",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604924490,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604924515,
      "name": "early_memunmap",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
```

```json
{
  "name": "early_memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604946017,
      "name": "early_memunmap",
      "external": true,
      "loc": "mm/early_ioremap.c:300",
      "file": "mm/early_ioremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/early_ioremap.c:copy_from_early_mem"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_read_phys_ulong",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__memory_setup_extended",
        "arch/x86/kernel/acpi/boot.c:__acpi_unmap_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:update_mp_table",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:default_get_smp_config",
        "arch/x86/kernel/mpparse.c:get_mpc_size",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/kernel/jailhouse.c:jailhouse_init_platform",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/quirks.c:efi_reuse_config",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "arch/x86/platform/efi/efi.c:efi_init",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/firmware/dmi_scan.c:dmi_setup",
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
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:efi_esrt_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604946042,
      "name": "early_memunmap",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void early_memunmap(void * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void early_memunmap(void * addr, long unsigned int size)
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
