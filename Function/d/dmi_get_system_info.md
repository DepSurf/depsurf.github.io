# Function: <code>dmi_get_system_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585984192,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:830",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show",
        "drivers/firmware/dmi-id.c:get_modalias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984192,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586391461,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:852",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390560,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586600309,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:852",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:nvenet_msi_disable",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599408,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586725141,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:877",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586724384,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587209445,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:877",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon_dmi_quirks.c:fbcon_platform_get_rotate",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587208688,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587509701,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:895",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587509312,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587690053,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:895",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/iommu/intel-iommu.c:domain_prepare_identity_map",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689552,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587969333,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587968864,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588176469,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588176000,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589041573,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:934",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589040944,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589050901,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:934",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/usb/host/xhci.c:xhci_compliance_mode_recovery_timer_quirk_check",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589050272,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588938277,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:935",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937648,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589646069,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:935",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645408,
      "name": "dmi_get_system_info",
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591147301,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:935",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591146528,
      "name": "dmi_get_system_info",
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592873589,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:941",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592872768,
      "name": "dmi_get_system_info",
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593312069,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:941",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593311264,
      "name": "dmi_get_system_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594068613,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:941",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/char/tpm/tpm_tis_core.c:tis_int_handler",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_global_suspend_mode_is_broken",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:dmi_id_init_attr_table",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594067808,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501484004,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501483272,
      "name": "dmi_get_system_info",
      "section": ".text",
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234024080,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234023492,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dmi_get_system_info",
      "external": false,
      "loc": "include/linux/dmi.h:120",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_get_system_info",
      "external": false,
      "loc": "include/linux/dmi.h:120",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_get_system_info",
      "external": false,
      "loc": "include/linux/dmi.h:120",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dmi_get_system_info",
      "external": false,
      "loc": "include/linux/dmi.h:120",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_get_system_info",
      "external": false,
      "loc": "include/linux/dmi.h:120",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dmi_get_system_info",
      "external": false,
      "loc": "include/linux/dmi.h:120",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587794901,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587794432,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587498325,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587497856,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588130997,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588130528,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```

```json
{
  "name": "dmi_get_system_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588248533,
      "name": "dmi_get_system_info",
      "external": true,
      "loc": "drivers/firmware/dmi_scan.c:898",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_match",
        "drivers/firmware/dmi_scan.c:dmi_get_date"
      ],
      "caller_func": [
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/iommu/intel-iommu.c:init_dmars",
        "drivers/gpu/drm/drm_panel_orientation_quirks.c:drm_get_panel_orientation_quirk",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:dmi_id_init",
        "drivers/firmware/dmi-id.c:get_modalias",
        "drivers/firmware/dmi-id.c:sys_dmi_field_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248064,
      "name": "dmi_get_system_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * dmi_get_system_info(int field)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const char * dmi_get_system_info(int field)
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
