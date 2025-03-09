# Function: <code>acpi_check_dsm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const u8 * uuid, int rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583543347,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:680",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle",
        "drivers/iommu/dmar.c:dmar_device_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543347,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
bool acpi_check_dsm(acpi_handle handle, const u8 * uuid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583864381,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:677",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864381,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool acpi_check_dsm(acpi_handle handle, const u8 * uuid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584003457,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:677",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003457,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584053024,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:677",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053024,
      "name": "acpi_check_dsm",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584319936,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:678",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319936,
      "name": "acpi_check_dsm",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584540544,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:678",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540544,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584637760,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:678",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584637760,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584837584,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837584,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584973312,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973312,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585669520,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:697",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-label.c:acpi_index_string_exist",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669520,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585794384,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:693",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-label.c:acpi_index_string_exist",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794384,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585674432,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:687",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674432,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586154720,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:701",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154720,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385680,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:701",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385680,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588635408,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:739",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588635408,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588923152,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:739",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588923152,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589222208,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:811",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-label.c:acpi_attr_is_visible",
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/intel/dmar.c:dmar_device_hotplug",
        "drivers/iommu/intel/dmar.c:dmar_get_dsm_handle",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable",
        "drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_consumer",
        "drivers/platform/x86/amd/wbrf.c:acpi_amd_wbrf_supported_producer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222208,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497387312,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497387312,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584920880,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920880,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584826752,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/acpi/nfit/core.c:acpi_nfit_add_dimm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826752,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584924896,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924896,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```

```json
{
  "name": "acpi_check_dsm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585031040,
      "name": "acpi_check_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:665",
      "file": "drivers/acpi/utils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_adxl.c:adxl_init",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/iommu/dmar.c:dmar_device_hotplug",
        "drivers/iommu/dmar.c:dmar_get_dsm_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031040,
      "name": "acpi_check_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rev</code> ➡️ <code>u64 rev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const guid_t * guid</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 * uuid</code>
</li>
</ul>
</details>
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
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool acpi_check_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 funcs)
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
