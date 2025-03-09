# Function: <code>__dev_fwnode_const</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct fwnode_handle * __dev_fwnode_const(const struct device * dev)
```

```json
{
  "name": "__dev_fwnode_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590335061,
      "name": "__dev_fwnode_const",
      "external": true,
      "loc": "drivers/base/property.c:27",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node"
      ],
      "caller_func": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332048,
      "name": "__dev_fwnode_const",
      "section": ".text",
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
const struct fwnode_handle * __dev_fwnode_const(const struct device * dev)
```

```json
{
  "name": "__dev_fwnode_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590655109,
      "name": "__dev_fwnode_const",
      "external": true,
      "loc": "drivers/base/property.c:27",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/usb/roles/class.c:usb_role_switch_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590652064,
      "name": "__dev_fwnode_const",
      "section": ".text",
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
const struct fwnode_handle * __dev_fwnode_const(const struct device * dev)
```

```json
{
  "name": "__dev_fwnode_const",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591015253,
      "name": "__dev_fwnode_const",
      "external": true,
      "loc": "drivers/base/property.c:27",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_match_data",
        "drivers/base/property.c:device_get_dma_attr",
        "drivers/base/property.c:device_dma_supported",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_u64_array",
        "drivers/base/property.c:device_property_read_u32_array",
        "drivers/base/property.c:device_property_read_u16_array",
        "drivers/base/property.c:device_property_read_u8_array",
        "drivers/base/property.c:device_property_present"
      ],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/usb/roles/class.c:usb_role_switch_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591012208,
      "name": "__dev_fwnode_const",
      "section": ".text",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
const struct fwnode_handle * __dev_fwnode_const(const struct device * dev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
