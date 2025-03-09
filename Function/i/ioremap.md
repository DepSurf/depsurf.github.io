# Function: <code>ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578947937,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057987,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100067,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595076536,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595078279,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580464985,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:ioremap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050695,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583051076,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289461,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319401,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583523442,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583527331,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530655,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583596033,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583776302,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583847557,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595249096,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085398,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584190808,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584225437,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587345855,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595315046,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/dmi_scan.c:dmi_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595322434,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/firmware/efi/esrt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586162480,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578944652,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054369,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099587,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595242672,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595244980,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580541785,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:ioremap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344749,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583600609,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583630396,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844274,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848157,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851497,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919279,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584102309,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584180005,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595430809,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584416250,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530109,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584565190,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846070,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585055142,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595509546,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/firmware/efi/esrt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586575680,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578945116,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053473,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097715,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595486697,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595488892,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580605833,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:ioremap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583470125,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583737777,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767692,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583983522,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583987405,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583990857,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060180,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241956,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584250261,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361365,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595683124,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584598058,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712237,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584747078,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588061190,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585238426,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595766472,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586757232,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578938148,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045697,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089667,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596408004,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596409883,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580635721,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:ioremap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492363,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492788,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583779585,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583809758,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583903004,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584031793,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584035601,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584038965,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584042263,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/efifb.c:efifb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584121865,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584318734,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584327909,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584442966,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596607479,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584680164,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584794365,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584831111,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596621871,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588287878,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585320635,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596695560,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884068,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:192",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578940324,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054417,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100451,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602732590,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602734586,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583673579,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583674004,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584039713,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584073038,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584166238,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295665,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584299473,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584302869,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584306524,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/efifb.c:efifb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584393209,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584718123,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584732229,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853030,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602937857,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585093060,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585214653,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585253076,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585288120,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588853174,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585748362,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603025652,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/firmware/efi/apple-properties.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603027977,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578942832,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059338,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105970,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602904892,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602906822,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/early_printk.c:early_efi_map_fb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891355,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891806,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584236513,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272947,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584345364,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584384361,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584515425,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584519309,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523797,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526070,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584615146,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584945563,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584960906,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585081541,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603110765,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585327184,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585451370,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585489680,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585526372,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589232329,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585994314,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587090065,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/i2c/busses/i2c-amd-pci-mp2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603200661,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:210",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578944880,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063914,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111602,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604669765,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702445,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604704435,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "arch/x86/platform/efi/early_printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/early_printk.c:early_efi_map_fb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583975604,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583976078,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584326037,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584366723,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584440644,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584476201,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584612292,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616173,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584620669,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584623152,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584712537,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585049521,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065274,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585193653,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604913478,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585450640,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585574634,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585612179,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585650464,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475129,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_validate_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586131162,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605010953,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:211",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578950448,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960543,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072490,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121538,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604768663,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604802733,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158333,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584158776,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584521237,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584560832,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638312,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673977,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584810501,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584814431,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584819011,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821453,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584915581,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585253707,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269466,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585401909,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605022243,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585666511,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585794694,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585829136,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585874008,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937495,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586366124,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588010348,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578952880,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962975,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074490,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123410,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794501,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604828460,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468756,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584292077,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584292520,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584656357,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697616,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584776008,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584812249,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584945541,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584949471,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584954051,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584956500,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585051293,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585391595,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585407418,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585543669,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605059194,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585807487,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937446,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585971792,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586016568,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080679,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586514172,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588217990,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404624,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:efi_ioremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404624,
      "name": "ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405200,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:324",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:intel_i9xx_setup_flush",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405200,
      "name": "ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408432,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:326",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408432,
      "name": "ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471056,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:326",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471056,
      "name": "ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548304,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:331",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548304,
      "name": "ioremap",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653264,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:338",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653264,
      "name": "ioremap",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667488,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:343",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/platform/x86/intel/pmc/core.c:get_primary_reg_base",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_init",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667488,
      "name": "ioremap",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702048,
      "name": "ioremap",
      "external": true,
      "loc": "arch/x86/mm/ioremap.c:343",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:__uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_mmio_init_box",
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom",
        "arch/x86/kernel/quirks.c:ich_force_enable_hpet",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_log_read",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/eisa.c:eisa_bus_probe",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "lib/pci_iomap.c:pci_iomap",
        "lib/devres.c:devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/quirks.c:asus_hides_smbus_lpc_ich6_suspend",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpit.c:lpit_update_residency",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/hpet.c:hpet_resources",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init",
        "drivers/char/agp/intel-gtt.c:i810_setup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_validate_one_drhd",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/mmconfig_64.c:pci_mmcfg_arch_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702048,
      "name": "ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * ioremap(resource_size_t res_cookie, size_t size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224498700,
      "name": "ioremap",
      "external": true,
      "loc": "arch/arm/mm/ioremap.c:377",
      "file": "arch/arm/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/crash_dump.c:copy_oldmem_page",
        "arch/arm/mm/cache-l2x0.c:l2x0_of_init",
        "arch/arm/mach-berlin/platsmp.c:berlin_smp_prepare_cpus",
        "arch/arm/mach-exynos/platsmp.c:exynos_scu_enable",
        "arch/arm/mach-highbank/highbank.c:highbank_init_irq",
        "arch/arm/mach-hisi/platmcpm.c:hip04_smp_init",
        "arch/arm/mach-hisi/platsmp.c:hix5hd2_boot_secondary",
        "arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9",
        "arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_setup_boot_addr_wa",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init",
        "arch/arm/mach-imx/pm-imx6.c:imx6_pm_get_base",
        "arch/arm/mach-imx/mach-imx51.c:imx51_dt_init",
        "arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init",
        "arch/arm/mach-omap2/timer.c:realtime_counter_init",
        "arch/arm/mach-omap2/dma.c:omap2_system_dma_init_dev",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init_module",
        "arch/arm/mach-omap2/omap4-common.c:omap4_sar_ram_init",
        "arch/arm/mach-omap2/omap4-common.c:omap_l2_cache_init",
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_prepare_cpus",
        "arch/arm/mach-omap2/prm_common.c:omap2_prm_base_init",
        "arch/arm/mach-omap2/cm_common.c:omap2_cm_base_init",
        "arch/arm/mach-omap2/omap_phy_internal.c:__omap4430_phy_power_down",
        "arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_generic_init",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of",
        "arch/arm/mach-shmobile/setup-r8a7778.c:r8a7778_init_irq_dt",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init",
        "arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk",
        "arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init",
        "arch/arm/mach-shmobile/pm-rcar-gen2.c:rcar_gen2_pm_init",
        "arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus",
        "arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus",
        "fs/pstore/ram_core.c:persistent_ram_new",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_init",
        "drivers/irqchip/irq-orion.c:orion_irq_init",
        "drivers/irqchip/irq-omap-intc.c:omap_init_irq_legacy",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/omap_l3_smx.c:omap3_l3_probe",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/mx3fb.c:mx3fb_probe",
        "drivers/amba/bus.c:amba_device_try_add",
        "drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init",
        "drivers/clk/clk-qoriq.c:clockgen_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx53_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx51_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/imx/clk-imx5.c:mx50_clocks_init",
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init",
        "drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init",
        "drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_prepare_cpus",
        "drivers/soc/tegra/fuse/fuse-tegra.c:tegra_init_fuse",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc",
        "drivers/soc/tegra/flowctrl.c:tegra_flowctrl_init",
        "drivers/soc/tegra/pmc.c:tegra_pmc_early_init",
        "drivers/soc/tegra/pmc.c:tegra186_pmc_setup_irq_polarity",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/mfd/sm501.c:sm501_plat_probe",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/asic3.c:asic3_probe",
        "drivers/mfd/t7l66xb.c:t7l66xb_probe",
        "drivers/mfd/tc6387xb.c:tc6387xb_probe",
        "drivers/mfd/tc6393xb.c:tc6393xb_probe",
        "drivers/mfd/syscon.c:of_syscon_register",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/clocksource/timer-imx-gpt.c:mxc_timer_init",
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_iomap",
        "drivers/mailbox/pl320-ipc.c:pl320_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224498700,
      "name": "ioremap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * ioremap(phys_addr_t addr, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282725904,
      "name": "ioremap",
      "external": true,
      "loc": "arch/powerpc/mm/ioremap.c:11",
      "file": "arch/powerpc/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb",
        "arch/powerpc/kernel/eeh.c:eeh_dev_break_write",
        "arch/powerpc/kernel/legacy_serial.c:serial_dev_init",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/sysdev/i8259.c:i8259_init",
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node",
        "arch/powerpc/sysdev/xive/native.c:xive_native_init",
        "arch/powerpc/sysdev/xive/native.c:xive_native_populate_irq_data",
        "arch/powerpc/sysdev/xive/native.c:xive_native_populate_irq_data",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_populate_irq_data",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_populate_irq_data",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb",
        "arch/powerpc/platforms/powernv/vas-window.c:map_mmio_region",
        "arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_map_xsl_regs",
        "kernel/iomem.c:memremap",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/ecam.c:pci_ecam_create",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/video/console/vgacon.c:vgacon_startup",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_map_reg",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/char/agp/generic.c:agp_generic_create_gatt_table",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_vga_rw",
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_iomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282725904,
      "name": "ioremap",
      "section": ".text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * ioremap(phys_addr_t offset, long unsigned int size)
```

```json
{
  "name": "ioremap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271359836,
      "name": "ioremap",
      "external": true,
      "loc": "arch/riscv/mm/ioremap.c:66",
      "file": "arch/riscv/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/sifive_l2_cache.c:sifive_l2_init",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:memremap",
        "kernel/iomem.c:ioremap_cache",
        "lib/pci_iomap.c:pci_iomap_wc_range",
        "lib/pci_iomap.c:pci_iomap_range",
        "lib/devres.c:__devm_ioremap",
        "drivers/pci/pci.c:devm_pci_remap_cfgspace",
        "drivers/pci/pci.c:pci_ioremap_bar",
        "drivers/pci/rom.c:pci_map_rom",
        "drivers/pci/quirks.c:quirk_e100_interrupt",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/ecam.c:pci_ecam_create",
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/simplefb.c:simplefb_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init",
        "drivers/mfd/syscon.c:of_syscon_register",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_iomap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271359836,
      "name": "ioremap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578952880,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962975,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074842,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123794,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604708443,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604742340,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260813,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261256,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584606821,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584648096,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584724824,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584760985,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584896405,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584900335,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584904915,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584907360,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585177115,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585305701,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604958871,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585568479,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585698422,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585732768,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585777544,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585841799,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586204652,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586501142,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_remap_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587829686,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578950256,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960655,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007738,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055730,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676391,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604709942,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584196013,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584196456,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584536645,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584577872,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584655592,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584691769,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584898237,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585118811,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585129930,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557766,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585591952,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585636728,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585700839,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586023020,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586369718,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_remap_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587539398,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578952816,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962911,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074426,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123346,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604786010,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604819907,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584244573,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584245016,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584606517,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647776,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726168,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584762409,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584897829,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584901759,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584906339,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584908784,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585002877,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585341995,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585357818,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585494069,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605039517,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585757887,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585887462,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585921808,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585966584,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586030695,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586462140,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588172470,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578953392,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964047,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078522,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/probe_roms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/probe_roms.c:pci_map_biosrom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128466,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table",
        "arch/x86/kernel/tboot.c:tboot_get_dmar_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604798631,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/kernel/eisa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/eisa.c:eisa_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604832617,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474084,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349405,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/pci_iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/pci_iomap.c:pci_iomap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349848,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "lib/devres.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/devres.c:__devm_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584714213,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/rom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/rom.c:pci_map_rom"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755472,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_e100_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584833736,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/hotplug/shpchp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584869929,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/pci/endpoint/pci-epc-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585003205,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/imsttfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585007135,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/asiliantfb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585011715,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/vesafb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/vesafb.c:vesafb_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585014164,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/video/fbdev/efifb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585109053,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585449307,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585465098,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_exec_move_data",
        "drivers/acpi/apei/erst.c:erst_exec_move_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585602101,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_setup_auto_xlat_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605063374,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585865503,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585996486,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586029792,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:i9xx_setup",
        "drivers/char/agp/intel-gtt.c:i830_setup",
        "drivers/char/agp/intel-gtt.c:intel_gtt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586074312,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586138647,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_validate_one_drhd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/mfd/syscon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586573836,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290326,
      "name": "ioremap",
      "external": false,
      "loc": "arch/x86/include/asm/io.h:208",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * ioremap(resource_size_t phys_addr, long unsigned int size)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * ioremap(resource_size_t res_cookie, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * ioremap(phys_addr_t addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void * ioremap(phys_addr_t offset, long unsigned int size)
```
</details>
</li>
</ul>
