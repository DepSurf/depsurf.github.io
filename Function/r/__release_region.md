# Function: <code>__release_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396176,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1118",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_on_init_error",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396176,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408544,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1186",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_on_init_error",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408544,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428848,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1186",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_on_init_error",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428848,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416544,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1186",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416544,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444576,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1204",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444576,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459408,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1174",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459408,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493056,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1168",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493056,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510832,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510832,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536896,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536896,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566640,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1196",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/numa/hmat.c:hmat_free_structures",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_port",
        "drivers/tty/serial/8250/8250_core.c:univ8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/dmar.c:free_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566640,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547984,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1203",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/numa/hmat.c:hmat_free_structures",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_port",
        "drivers/tty/serial/8250/8250_core.c:univ8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/dmar.c:free_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547984,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552976,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1256",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_port",
        "drivers/tty/serial/8250/8250_core.c:univ8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552976,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625536,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1256",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625536,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721536,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1243",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721536,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849344,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1251",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849344,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899584,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1251",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_remove",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899584,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938320,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1306",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_release_region",
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_drvdata_release",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/bus.c:trim_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938320,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490683072,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/amba/bus.c:amba_release_regions",
        "drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup",
        "drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init",
        "drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup",
        "drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup",
        "drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init",
        "drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup",
        "drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver",
        "drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_exit_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/amba-pl011.c:pl011_release_port",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/tty/serial/msm_serial.c:msm_release_port",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_release_attrib",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490683072,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224751324,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init",
        "kernel/resource.c:devm_region_release",
        "fs/pstore/ram_core.c:persistent_ram_free",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/amba/bus.c:amba_release_regions",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/amba-pl011.c:pl011_release_port",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/tty/serial/msm_serial.c:msm_release_port",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224751324,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283506592,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node",
        "arch/powerpc/platforms/powernv/vas-window.c:vas_win_close",
        "arch/powerpc/platforms/powernv/vas-window.c:unmap_winctx_mmio_bars",
        "arch/powerpc/platforms/powernv/vas-window.c:unmap_winctx_mmio_bars",
        "kernel/resource.c:__devm_release_region",
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/gxt4500.c:gxt4500_remove",
        "drivers/video/fbdev/gxt4500.c:gxt4500_remove",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_destroy",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove",
        "drivers/input/serio/i8042.c:i8042_exit",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283506592,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271418110,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271418110,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510560,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510560,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439360,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/hv/vmbus_drv.c:vmbus_free_mmio",
        "drivers/hv/vmbus_drv.c:vmbus_free_mmio",
        "drivers/hv/vmbus_drv.c:vmbus_allocate_mmio",
        "drivers/hv/vmbus_drv.c:vmbus_acpi_remove",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439360,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510480,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510480,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void __release_region(struct resource * parent, resource_size_t start, resource_size_t n)
```

```json
{
  "name": "__release_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543296,
      "name": "__release_region",
      "external": true,
      "loc": "kernel/resource.c:1191",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_region_release",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/pci.c:pci_release_region",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr",
        "drivers/video/fbdev/imsttfb.c:imsttfb_remove",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_remove",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_destroy",
        "drivers/video/fbdev/efifb.c:efifb_destroy",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/apei-base.c:apei_resources_release",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/tty/serial/8250/8250_core.c:serial8250_release_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_release_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_exit",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_amd64_remove",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:dmar_free_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_release",
        "drivers/nvdimm/dimm_devs.c:nvdimm_free_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_remove",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543296,
      "name": "__release_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
