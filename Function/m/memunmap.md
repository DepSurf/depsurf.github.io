# Function: <code>memunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580464416,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/memremap.c:105",
      "file": "kernel/memremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_release"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464416,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539936,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/memremap.c:125",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "kernel/memremap.c:devm_memremap_release",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539936,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603968,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/memremap.c:125",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init",
        "kernel/memremap.c:devm_memremap_release",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603968,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633888,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/memremap.c:125",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/memremap.c:devm_memremap_release",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633888,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580715920,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/memremap.c:138",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/memremap.c:devm_memremap_release",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715920,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848320,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848320,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917200,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917200,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015360,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/dma/coherent.c:dma_release_declared_memory",
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015360,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070640,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070640,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581251838,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251568,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293806,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/ksysfs.c:create_setup_data_node",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293536,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581311662,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311392,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581556894,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556240,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908573,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/amd/init.c:copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_opregion_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907888,
      "name": "memunmap",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582343229,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342256,
      "name": "memunmap",
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582545597,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544640,
      "name": "memunmap",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715472,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:119",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/ksysfs.c:create_setup_data_nodes",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/acpi/prmt.c:acpi_parse_prmt",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/iommu/intel/iommu.c:copy_translation_tables",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/iommu.c:copy_context_table",
        "drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715472,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492431724,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "arch/arm64/kernel/crash_dump.c:copy_oldmem_page",
        "arch/arm64/kernel/crash_dump.c:copy_oldmem_page",
        "virt/kvm/kvm_main.c:__kvm_unmap_gfn",
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory",
        "drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492431608,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226307916,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_scan_machine",
        "drivers/firmware/dmi_scan.c:dmi_walk_early",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226307916,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285701824,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285701824,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272512316,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/iomem.c:devm_memremap_release"
      ],
      "caller_func": [
        "kernel/dma/coherent.c:dma_declare_coherent_memory",
        "kernel/dma/coherent.c:dma_init_coherent_memory",
        "drivers/nvdimm/core.c:nvdimm_map_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272512224,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039488,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039488,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580986768,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986768,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030688,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030688,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void memunmap(void * addr)
```

```json
{
  "name": "memunmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092128,
      "name": "memunmap",
      "external": true,
      "loc": "kernel/iomem.c:122",
      "file": "kernel/iomem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:boot_params_ksysfs_init",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:setup_data_data_read",
        "arch/x86/kernel/ksysfs.c:type_show",
        "arch/x86/kernel/ksysfs.c:get_setup_data_paddr",
        "arch/x86/mm/ioremap.c:unxlate_dev_mem_ptr",
        "arch/x86/platform/efi/quirks.c:efi_free_boot_services",
        "kernel/iomem.c:devm_memremap_release",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/bgrt.c:bgrt_init",
        "drivers/sfi/sfi_core.c:sfi_unmap_memory",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/amd_iommu_init.c:early_enable_iommus",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/iommu/intel-iommu.c:copy_translation_tables",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init",
        "drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_release",
        "drivers/firmware/dmi_scan.c:dmi_walk",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent",
        "drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions",
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "arch/x86/pci/common.c:pcibios_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092128,
      "name": "memunmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
