# Function: <code>of_get_next_parent</code>

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
struct device_node * of_get_next_parent(struct device_node * node)
```

```json
{
  "name": "of_get_next_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501598048,
      "name": "of_get_next_parent",
      "external": true,
      "loc": "drivers/of/base.c:712",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/vexpress-config.c:vexpress_config_find_prop",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/of/property.c:of_fwnode_graph_get_port_parent",
        "drivers/of/property.c:of_graph_get_remote_port",
        "drivers/of/address.c:of_dma_is_coherent",
        "drivers/of/of_numa.c:of_node_to_nid",
        "drivers/nvmem/core.c:of_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501598048,
      "name": "of_get_next_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct device_node * of_get_next_parent(struct device_node * node)
```

```json
{
  "name": "of_get_next_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234121116,
      "name": "of_get_next_parent",
      "external": true,
      "loc": "drivers/of/base.c:712",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/vexpress-config.c:vexpress_config_find_prop",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/of/property.c:of_fwnode_graph_get_port_parent",
        "drivers/of/property.c:of_graph_get_remote_port",
        "drivers/of/address.c:of_dma_is_coherent",
        "drivers/nvmem/core.c:of_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234121116,
      "name": "of_get_next_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device_node * of_get_next_parent(struct device_node * node)
```

```json
{
  "name": "of_get_next_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295012544,
      "name": "of_get_next_parent",
      "external": true,
      "loc": "drivers/of/base.c:712",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:of_get_ibm_chip_id",
        "arch/powerpc/mm/numa.c:of_node_to_nid",
        "arch/powerpc/platforms/pseries/pci.c:pseries_root_bridge_prepare",
        "arch/powerpc/platforms/pseries/msi.c:msi_quota_for_device",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/of/property.c:of_fwnode_graph_get_port_parent",
        "drivers/of/property.c:of_graph_get_remote_port",
        "drivers/nvmem/core.c:of_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295012544,
      "name": "of_get_next_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct device_node * of_get_next_parent(struct device_node * node)
```

```json
{
  "name": "of_get_next_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278063322,
      "name": "of_get_next_parent",
      "external": true,
      "loc": "drivers/of/base.c:712",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/pinctrl/devicetree.c:pinctrl_dt_to_map",
        "drivers/of/property.c:of_fwnode_graph_get_port_parent",
        "drivers/of/property.c:of_graph_get_remote_port",
        "drivers/of/address.c:of_dma_is_coherent",
        "drivers/nvmem/core.c:of_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278063322,
      "name": "of_get_next_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device_node * of_get_next_parent(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_get_next_parent(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_get_next_parent(struct device_node * node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_get_next_parent(struct device_node * node)
```
</details>
</li>
</ul>
