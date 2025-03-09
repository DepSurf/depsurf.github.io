# Function: <code>of_property_read_variable_u64_array</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u64_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501623624,
      "name": "of_property_read_variable_u64_array",
      "external": true,
      "loc": "drivers/of/property.c:350",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501623624,
      "name": "of_property_read_variable_u64_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u64_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234141232,
      "name": "of_property_read_variable_u64_array",
      "external": true,
      "loc": "drivers/of/property.c:350",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234141232,
      "name": "of_property_read_variable_u64_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u64_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295045920,
      "name": "of_property_read_variable_u64_array",
      "external": true,
      "loc": "drivers/of/property.c:350",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt",
        "arch/powerpc/platforms/powernv/idle.c:pnv_parse_cpuidle_dt",
        "arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init",
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295045920,
      "name": "of_property_read_variable_u64_array",
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
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```

```json
{
  "name": "of_property_read_variable_u64_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278085314,
      "name": "of_property_read_variable_u64_array",
      "external": true,
      "loc": "drivers/of/property.c:350",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/property.c:of_fwnode_property_read_int_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278085314,
      "name": "of_property_read_variable_u64_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_property_read_variable_u64_array(const struct device_node * np, const char * propname, u64 * out_values, size_t sz_min, size_t sz_max)
```
</details>
</li>
</ul>
