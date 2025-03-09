# Function: <code>of_property_read_variable_u8_array</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_property_read_variable_u8_array",
      "external": false,
      "loc": "include/linux/of.h:650",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_property_read_variable_u8_array",
      "external": false,
      "loc": "include/linux/of.h:648",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_property_read_variable_u8_array",
      "external": false,
      "loc": "include/linux/of.h:670",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_property_read_variable_u8_array",
      "external": false,
      "loc": "include/linux/of.h:669",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501617648,
      "name": "of_property_read_variable_u8_array",
      "external": true,
      "loc": "drivers/of/property.c:183",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501617648,
      "name": "of_property_read_variable_u8_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234140440,
      "name": "of_property_read_variable_u8_array",
      "external": true,
      "loc": "drivers/of/property.c:183",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234140440,
      "name": "of_property_read_variable_u8_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295044752,
      "name": "of_property_read_variable_u8_array",
      "external": true,
      "loc": "drivers/of/property.c:183",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init",
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295044752,
      "name": "of_property_read_variable_u8_array",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u8_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278080478,
      "name": "of_property_read_variable_u8_array",
      "external": true,
      "loc": "drivers/of/property.c:183",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init",
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278080478,
      "name": "of_property_read_variable_u8_array",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_property_read_variable_u8_array(const struct device_node * np, const char * propname, u8 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
</ul>
