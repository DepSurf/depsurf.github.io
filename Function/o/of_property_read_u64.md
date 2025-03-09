# Function: <code>of_property_read_u64</code>

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
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```

```json
{
  "name": "of_property_read_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501623448,
      "name": "of_property_read_u64",
      "external": true,
      "loc": "drivers/of/property.c:315",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_init",
        "drivers/irqchip/irq-gic-v3.c:gic_of_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501623448,
      "name": "of_property_read_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```

```json
{
  "name": "of_property_read_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234141104,
      "name": "of_property_read_u64",
      "external": true,
      "loc": "drivers/of/property.c:315",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_of_init",
        "drivers/soc/renesas/r9a06g032-smp.c:r9a06g032_smp_prepare_cpus",
        "drivers/mmc/host/sdhci.c:__sdhci_read_caps",
        "drivers/mmc/host/sdhci.c:__sdhci_read_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234141104,
      "name": "of_property_read_u64",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```

```json
{
  "name": "of_property_read_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295045696,
      "name": "of_property_read_u64",
      "external": true,
      "loc": "drivers/of/property.c:315",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller",
        "arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init",
        "arch/powerpc/platforms/powernv/opal-msglog.c:memcons_init",
        "arch/powerpc/platforms/powernv/pci.c:pnv_pci_get_slot_id",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_ibm_npu2_init",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295045696,
      "name": "of_property_read_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```

```json
{
  "name": "of_property_read_u64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278085106,
      "name": "of_property_read_u64",
      "external": true,
      "loc": "drivers/of/property.c:315",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278085106,
      "name": "of_property_read_u64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_property_read_u64(const struct device_node * np, const char * propname, u64 * out_value)
```
</details>
</li>
</ul>
