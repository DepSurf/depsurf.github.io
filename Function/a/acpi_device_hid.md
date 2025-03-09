# Function: <code>acpi_device_hid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583560764,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1147",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/spi/spi.c:acpi_spi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583560764,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882430,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1167",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882430,
      "name": "acpi_device_hid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021517,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1165",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021517,
      "name": "acpi_device_hid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584079806,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1156",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075072,
      "name": "acpi_device_hid",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584349646,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1160",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344720,
      "name": "acpi_device_hid",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584570726,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1161",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565712,
      "name": "acpi_device_hid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584668038,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1161",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:find_powerf_dev",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:hid_uid_match",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663024,
      "name": "acpi_device_hid",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584868243,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:hid_uid_match",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863168,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585004115,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:hid_uid_match",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999040,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585706220,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1168",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697840,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585828255,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1237",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819584,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585707343,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1236",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699920,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586186834,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1244",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/gpu/vga/vgaarb.c:vga_arb_select_default_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586180432,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587422846,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1274",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn"
      ],
      "caller_func": [
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415712,
      "name": "acpi_device_hid",
      "section": ".text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588681657,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1257",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn"
      ],
      "caller_func": [
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588672224,
      "name": "acpi_device_hid",
      "section": ".text",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588969417,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1259",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn"
      ],
      "caller_func": [
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/utils.c:acpi_dev_hid_uid_match",
        "drivers/acpi/device_sysfs.c:hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959968,
      "name": "acpi_device_hid",
      "section": ".text",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589266873,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1262",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn"
      ],
      "caller_func": [
        "drivers/pci/vgaarb.c:vga_is_boot_device",
        "drivers/acpi/device_sysfs.c:hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257312,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497414572,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497408704,
      "name": "acpi_device_hid",
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584947811,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942944,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584856611,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:hid_uid_match",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851744,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584955699,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:hid_uid_match",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950624,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
const char * acpi_device_hid(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_hid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585061875,
      "name": "acpi_device_hid",
      "external": true,
      "loc": "drivers/acpi/scan.c:1159",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:acpi_device_hid_show",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pci_root.c:acpi_pci_root_add",
        "drivers/acpi/acpi_lpss.c:hid_uid_match",
        "drivers/acpi/button.c:acpi_button_add",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585056800,
      "name": "acpi_device_hid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const char * acpi_device_hid(struct acpi_device * device)
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
