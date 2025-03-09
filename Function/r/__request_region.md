# Function: <code>__request_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396784,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1061",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396784,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409152,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1127",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409152,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429456,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1127",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429456,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417104,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1127",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417104,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445136,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1145",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445136,
      "name": "__request_region",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459920,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1115",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459920,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493568,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1109",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493568,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515255,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579511392,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541355,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579537456,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:alloc_memory_target",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:univ8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573014,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579567392,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1130",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:alloc_memory_target",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:univ8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591278591,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579548736,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554576,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1222",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:univ8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554576,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627136,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1222",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627136,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721152,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1209",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721152,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848928,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1217",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dax/hmem/device.c:hmem_register_device",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848928,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899168,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1217",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/efifb.c:efifb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899168,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937856,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1272",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:register_memory_resource",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/apei-base.c:apei_resources_request",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:probe_setup_port",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid",
        "drivers/iommu/amd/init.c:init_iommu_one",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/iommu/intel/dmar.c:map_iommu",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937856,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490683624,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/controller/pci-thunder-pem.c:thunder_pem_reserve_range",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/amba/bus.c:amba_request_regions",
        "drivers/reset/reset-sunxi.c:sun6i_reset_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/amba-pl011.c:pl011_request_port",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe",
        "drivers/edac/altera_edac.c:altr_sdram_probe",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_frame_register",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490683624,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224752264,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/cpu-reset.c:mvebu_cpu_reset_init",
        "arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_init",
        "arch/arm/mach-mvebu/pm.c:mvebu_pm_suspend_init",
        "kernel/resource.c:__devm_request_region",
        "fs/pstore/ram_core.c:persistent_ram_new",
        "drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init",
        "drivers/irqchip/irq-orion.c:orion_bridge_irq_init",
        "drivers/irqchip/irq-orion.c:orion_irq_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/omap2/omapfb/vrfb.c:omap_vrfb_request_ctx",
        "drivers/amba/bus.c:amba_request_regions",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/tty/serial/amba-pl011.c:pl011_request_port",
        "drivers/tty/serial/msm_serial.c:msm_request_port",
        "drivers/mfd/sm501.c:sm501_pci_probe",
        "drivers/mfd/sm501.c:sm501_plat_probe",
        "drivers/mfd/sm501.c:sm501_init_dev",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_mem_of_init",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224752264,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283507776,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node",
        "arch/powerpc/platforms/powernv/vas-window.c:map_mmio_region",
        "arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup",
        "arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup",
        "arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup",
        "arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup",
        "arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup",
        "arch/powerpc/platforms/pseries/pci.c:pSeries_final_fixup",
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/gxt4500.c:gxt4500_probe",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove",
        "drivers/input/serio/i8042.c:i8042_init",
        "drivers/of/address.c:of_io_request_and_map",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283507776,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271417562,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/of/address.c:of_io_request_and_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271417562,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515019,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579511120,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "drivers/hv/vmbus_drv.c:vmbus_acpi_add",
        "drivers/hv/vmbus_drv.c:vmbus_allocate_mmio",
        "drivers/hv/vmbus_drv.c:vmbus_allocate_mmio",
        "drivers/hv/vmbus_drv.c:vmbus_allocate_mmio",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443819,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579439920,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514939,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579511040,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct resource * __request_region(struct resource * parent, resource_size_t start, resource_size_t n, const char * name, int flags)
```

```json
{
  "name": "__request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__request_region",
      "external": true,
      "loc": "kernel/resource.c:1123",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__devm_request_region",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/pci.c:__pci_request_region",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/quirks.c:quirk_ati_exploding_mce",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/video/fbdev/imsttfb.c:imsttfb_probe",
        "drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/video/fbdev/vesafb.c:vesafb_probe",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/osl.c:acpi_request_region",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt",
        "drivers/acpi/apei/erst.c:erst_init",
        "drivers/pnp/resource.c:pnp_check_mem",
        "drivers/pnp/resource.c:pnp_check_port",
        "drivers/pnp/system.c:reserve_range",
        "drivers/pnp/system.c:reserve_range",
        "drivers/tty/serial/8250/8250_core.c:serial8250_request_rsa_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource",
        "drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key",
        "drivers/tty/serial/8250/8250_pci.c:pci_ite887x_init",
        "drivers/iommu/amd_iommu_init.c:init_iommu_all",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/dimm_devs.c:nvdimm_allocate_dpa",
        "drivers/rtc/rtc-cmos.c:cmos_do_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/fixup.c:quirk_apple_mbp_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547897,
      "name": "__request_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579543936,
      "name": "__request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
