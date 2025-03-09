# Function: <code>of_n_size_cells</code>

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
int of_n_size_cells(struct device_node * np)
```

```json
{
  "name": "of_n_size_cells",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501593304,
      "name": "of_n_size_cells",
      "external": true,
      "loc": "drivers/of/base.c:104",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe",
        "drivers/iommu/of_iommu.c:of_get_dma_window",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_bus_default_count_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501593304,
      "name": "of_n_size_cells",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int of_n_size_cells(struct device_node * np)
```

```json
{
  "name": "of_n_size_cells",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234120772,
      "name": "of_n_size_cells",
      "external": true,
      "loc": "drivers/of/base.c:104",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/of_iommu.c:of_get_dma_window",
        "drivers/mtd/parsers/ofpart.c:parse_fixed_partitions",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_bus_default_count_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234120772,
      "name": "of_n_size_cells",
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
int of_n_size_cells(struct device_node * np)
```

```json
{
  "name": "of_n_size_cells",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295011984,
      "name": "of_n_size_cells",
      "external": true,
      "loc": "drivers/of/base.c:104",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/prom_parse.c:of_parse_dma_window",
        "arch/powerpc/kernel/ima_kexec.c:get_addr_size_cells",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node",
        "arch/powerpc/platforms/pseries/iommu.c:enable_ddw",
        "drivers/iommu/of_iommu.c:of_get_dma_window",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_bus_default_count_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295011984,
      "name": "of_n_size_cells",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int of_n_size_cells(struct device_node * np)
```

```json
{
  "name": "of_n_size_cells",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278062882,
      "name": "of_n_size_cells",
      "external": true,
      "loc": "drivers/of/base.c:104",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_bus_default_count_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278062882,
      "name": "of_n_size_cells",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int of_n_size_cells(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_n_size_cells(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_n_size_cells(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_n_size_cells(struct device_node * np)
```
</details>
</li>
</ul>
