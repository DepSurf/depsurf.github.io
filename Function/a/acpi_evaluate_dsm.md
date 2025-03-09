# Function: <code>acpi_evaluate_dsm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const u8 * uuid, int rev, int func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583542842,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:631",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583542842,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const u8 * uuid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863783,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:628",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863783,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const u8 * uuid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002859,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:628",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002859,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584052112,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:628",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052112,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319024,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:629",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319024,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539328,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:629",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539328,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584636544,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:629",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584636544,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584836368,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584836368,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972096,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972096,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669232,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:648",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_optimize_delay",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669232,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793056,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:644",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_optimize_delay",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793056,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672832,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:638",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672832,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152400,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:652",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:validate_dsm",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152400,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385344,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:652",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/utils.c:acpi_check_dsm",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:validate_dsm",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385344,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588635056,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:690",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/utils.c:acpi_check_dsm",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:validate_dsm",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588635056,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922800,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:690",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/utils.c:acpi_check_dsm",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:validate_dsm",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922800,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221856,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:762",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/edr.c:pci_acpi_add_edr_notifier",
        "drivers/pci/pcie/edr.c:edr_handle_event",
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/utils.c:acpi_check_dsm",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/s2idle.c:validate_dsm",
        "drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints",
        "drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/char/tpm/tpm_crb.c:crb_send",
        "drivers/iommu/intel/dmar.c:dmar_walk_dsm_resource",
        "drivers/usb/core/usb-acpi.c:usb_acpi_port_lpm_incapable",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/platform/x86/amd/wbrf.c:amd_wbrf_retrieve_freq_band",
        "drivers/platform/x86/amd/wbrf.c:wbrf_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221856,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497386144,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497386144,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584919664,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919664,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584825536,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/acpi/nfit/core.c:nfit_intel_shutdown_status",
        "drivers/acpi/nfit/core.c:acpi_nfit_ctl",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584825536,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923680,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923680,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```

```json
{
  "name": "acpi_evaluate_dsm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585029824,
      "name": "acpi_evaluate_dsm",
      "external": true,
      "loc": "drivers/acpi/utils.c:616",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:pci_acpi_setup",
        "drivers/pci/pci-acpi.c:acpi_pci_add_bus",
        "drivers/acpi/sleep.c:lpi_device_get_constraints",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/x86/apple.c:acpi_extract_apple_properties",
        "drivers/acpi/acpi_adxl.c:adxl_dsm",
        "drivers/char/tpm/tpm_ppi.c:tpm_add_ppi",
        "drivers/char/tpm/tpm_ppi.c:show_ppi_operations",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_response",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_transition_action",
        "drivers/char/tpm/tpm_ppi.c:tpm_store_ppi_request",
        "drivers/char/tpm/tpm_ppi.c:tpm_show_ppi_request",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029824,
      "name": "acpi_evaluate_dsm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<li>
<b>Param type changed. </b>
<code>int func</code> ➡️ <code>u64 func</code>
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
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
union acpi_object * acpi_evaluate_dsm(acpi_handle handle, const guid_t * guid, u64 rev, u64 func, union acpi_object * argv4)
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
