# Function: <code>of_find_node_by_phandle</code>

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
struct device_node * of_find_node_by_phandle(phandle handle)
```

```json
{
  "name": "of_find_node_by_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501600304,
      "name": "of_find_node_by_phandle",
      "external": true,
      "loc": "drivers/of/base.c:1222",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions",
        "drivers/irqchip/irq-gic-v3.c:partition_domain_translate",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions",
        "drivers/of/base.c:of_map_rid",
        "drivers/of/base.c:of_parse_phandle_with_args_map",
        "drivers/of/base.c:of_phandle_iterator_next",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501600304,
      "name": "of_find_node_by_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
struct device_node * of_find_node_by_phandle(phandle handle)
```

```json
{
  "name": "of_find_node_by_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234123752,
      "name": "of_find_node_by_phandle",
      "external": true,
      "loc": "drivers/of/base.c:1222",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions",
        "drivers/irqchip/irq-gic-v3.c:partition_domain_translate",
        "drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt",
        "drivers/of/base.c:of_map_rid",
        "drivers/of/base.c:of_parse_phandle_with_args_map",
        "drivers/of/base.c:of_phandle_iterator_next",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234123752,
      "name": "of_find_node_by_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct device_node * of_find_node_by_phandle(phandle handle)
```

```json
{
  "name": "of_find_node_by_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295018912,
      "name": "of_find_node_by_phandle",
      "external": true,
      "loc": "drivers/of/base.c:1222",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update",
        "arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update",
        "arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update",
        "arch/powerpc/platforms/pseries/mobility.c:pseries_devicetree_update",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init",
        "drivers/of/base.c:of_map_rid",
        "drivers/of/base.c:of_parse_phandle_with_args_map",
        "drivers/of/base.c:of_phandle_iterator_next",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_get_by_phandle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295018912,
      "name": "of_find_node_by_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
struct device_node * of_find_node_by_phandle(phandle handle)
```

```json
{
  "name": "of_find_node_by_phandle",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278065750,
      "name": "of_find_node_by_phandle",
      "external": true,
      "loc": "drivers/of/base.c:1222",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/of/base.c:of_map_rid",
        "drivers/of/base.c:of_parse_phandle_with_args_map",
        "drivers/of/base.c:of_phandle_iterator_next",
        "drivers/of/irq.c:of_irq_parse_raw",
        "drivers/of/overlay.c:init_overlay_changeset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278065750,
      "name": "of_find_node_by_phandle",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct device_node * of_find_node_by_phandle(phandle handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_find_node_by_phandle(phandle handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_find_node_by_phandle(phandle handle)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_find_node_by_phandle(phandle handle)
```
</details>
</li>
</ul>
