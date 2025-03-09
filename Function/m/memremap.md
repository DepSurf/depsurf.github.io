# Function: <code>memremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580464992,
      "name": "memremap",
      "external": true,
      "loc": "kernel/memremap.c:58",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464992,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541792,
      "name": "memremap",
      "external": true,
      "loc": "kernel/memremap.c:74",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "kernel/memremap.c:devm_memremap",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541792,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580605840,
      "name": "memremap",
      "external": true,
      "loc": "kernel/memremap.c:74",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "kernel/memremap.c:devm_memremap",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605840,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635728,
      "name": "memremap",
      "external": true,
      "loc": "kernel/memremap.c:74",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/memremap.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635728,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715536,
      "name": "memremap",
      "external": true,
      "loc": "kernel/memremap.c:87",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/memremap.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715536,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847920,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847920,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916800,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916800,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014912,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014912,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070192,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070192,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251296,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251296,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293264,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293264,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311056,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311056,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/efi.c:efi_debugfs_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188992,
      "name": "memremap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581556336,
      "name": "memremap",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/iomem.c:devm_memremap",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964094,
      "name": "memremap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071581908032,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/dma/swiotlb.c:swiotlb_update_mem_attributes",
        "kernel/iomem.c:devm_memremap",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_memreserve_root_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "drivers/clocksource/hyperv_timer.c:hv_remap_tsc_clocksource",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023719,
      "name": "memremap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582342656,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_memreserve_root_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "drivers/clocksource/hyperv_timer.c:hv_remap_tsc_clocksource",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596546005,
      "name": "memremap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582545040,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:68",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/kernel/acpi/boot.c:acpi_wakeup_cpu",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_memreserve_root_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "drivers/clocksource/hyperv_timer.c:hv_remap_tsc_clocksource",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449784,
      "name": "memremap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582715728,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492432104,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/crash_dump.c:copy_oldmem_page",
        "virt/kvm/kvm_main.c:__kvm_map_gfn",
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "kernel/iomem.c:devm_memremap",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/soc/qcom/cmd-db.c:cmd_db_dev_probe",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492432104,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226308108,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "kernel/iomem.c:devm_memremap",
        "drivers/irqchip/irq-gic-v3-its.c:its_init",
        "drivers/soc/qcom/cmd-db.c:cmd_db_dev_probe",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226308108,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285701216,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "kernel/iomem.c:devm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285701216,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272512492,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "kernel/iomem.c:devm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272512492,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039040,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039040,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986320,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986320,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030240,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030240,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void * memremap(resource_size_t offset, size_t size, long unsigned int flags)
```

```json
{
  "name": "memremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091680,
      "name": "memremap",
      "external": true,
      "loc": "kernel/iomem.c:71",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:xlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_map_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_memreserve_map_root",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:__efi_memmap_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091680,
      "name": "memremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
