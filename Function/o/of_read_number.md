# Function: <code>of_read_number</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u64 of_read_number(const __be32 * cell, int size)
```

```json
{
  "name": "of_read_number",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510822884,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496452276,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/bus/fsl-mc/fsl-mc-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe",
        "drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe"
      ]
    },
    {
      "addr": 18446603336498866824,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/iommu/of_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/of_iommu.c:of_get_dma_window",
        "drivers/iommu/of_iommu.c:of_get_dma_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511279992,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:fdt_find_uefi_params"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501623744,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/property.c:of_property_read_variable_u64_array",
        "drivers/of/property.c:of_property_read_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501633828,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:dt_mem_next_cell"
      ]
    },
    {
      "addr": 18446603336501634092,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt_address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_translate",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map"
      ]
    },
    {
      "addr": 18446603336501641772,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_get_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_get_pci_address",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_default_translate",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511309368,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/of_reserved_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501660636,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/of_numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_numa.c:of_numa_init",
        "drivers/of/of_numa.c:of_numa_init",
        "drivers/of/of_numa.c:of_numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496452276,
      "name": "of_read_number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336501633828,
      "name": "of_read_number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336501634092,
      "name": "of_read_number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446603336501660636,
      "name": "of_read_number.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "of_read_number",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243570444,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/bus/mvebu-mbus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init",
        "drivers/bus/mvebu-mbus.c:mvebu_mbus_dt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3230307796,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/pci/controller/pci-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pci-mvebu.c:mvebu_get_tgt_attr",
        "drivers/pci/controller/pci-mvebu.c:mvebu_get_tgt_attr",
        "drivers/pci/controller/pci-mvebu.c:mvebu_get_tgt_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 3231454008,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/iommu/of_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/of_iommu.c:of_get_dma_window",
        "drivers/iommu/of_iommu.c:of_get_dma_window"
      ],
      "caller_func": []
    },
    {
      "addr": 3232331768,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/mtd/parsers/ofpart.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/parsers/ofpart.c:parse_fixed_partitions",
        "drivers/mtd/parsers/ofpart.c:parse_fixed_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 3243932100,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:fdt_find_uefi_params"
      ],
      "caller_func": []
    },
    {
      "addr": 3234127984,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id"
      ],
      "caller_func": []
    },
    {
      "addr": 3234138504,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_bus_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3234141352,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/property.c:of_property_read_variable_u64_array",
        "drivers/of/property.c:of_property_read_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 3243962312,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:dt_mem_next_cell"
      ],
      "caller_func": []
    },
    {
      "addr": 3243967972,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt_address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/fdt_address.c:of_flat_dt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_translate",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3234161276,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_get_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_get_pci_address",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_default_translate",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3243969864,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/of_reserved_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "of_read_number",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282336464,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302384348,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/time.c:get_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302388816,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/prom.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282363836,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/prom_parse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/prom_parse.c:of_parse_dma_window",
        "arch/powerpc/kernel/prom_parse.c:of_parse_dma_window",
        "arch/powerpc/kernel/prom_parse.c:of_parse_dma_window",
        "arch/powerpc/kernel/prom_parse.c:of_parse_dma_window",
        "arch/powerpc/kernel/prom_parse.c:of_parse_dma_window"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282481284,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/fadump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302421320,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/legacy_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282598388,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/pci_dn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci_dn.c:pci_traverse_device_nodes",
        "arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info",
        "arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info",
        "arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info",
        "arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info",
        "arch/powerpc/kernel/pci_dn.c:pci_add_device_node_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302423256,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/isa-bridge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/isa-bridge.c:isa_bridge_init_non_pci"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282620976,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/pci_of_scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci_of_scan.c:__of_scan_bus",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/kernel/pci_of_scan.c:get_int_prop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282632620,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/kernel/ima_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ima_kexec.c:do_get_kexec_buffer",
        "arch/powerpc/kernel/ima_kexec.c:do_get_kexec_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302433208,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/mm/drmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/drmem.c:drmem_init",
        "arch/powerpc/mm/drmem.c:drmem_init",
        "arch/powerpc/mm/drmem.c:__walk_drmem_v2_lmbs",
        "arch/powerpc/mm/drmem.c:read_drconf_v2_cell",
        "arch/powerpc/mm/drmem.c:read_drconf_v2_cell",
        "arch/powerpc/mm/drmem.c:read_drconf_v2_cell",
        "arch/powerpc/mm/drmem.c:read_drconf_v2_cell",
        "arch/powerpc/mm/drmem.c:__walk_drmem_v1_lmbs",
        "arch/powerpc/mm/drmem.c:read_drconf_v1_cell",
        "arch/powerpc/mm/drmem.c:read_drconf_v1_cell",
        "arch/powerpc/mm/drmem.c:read_drconf_v1_cell"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282830936,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:hot_add_scn_to_nid",
        "arch/powerpc/mm/numa.c:hot_add_scn_to_nid",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:parse_numa_properties",
        "arch/powerpc/mm/numa.c:numa_setup_drmem_lmb",
        "arch/powerpc/mm/numa.c:numa_setup_drmem_lmb",
        "arch/powerpc/mm/numa.c:numa_setup_drmem_lmb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302452572,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/sysdev/xics/icp-native.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node",
        "arch/powerpc/sysdev/xics/icp-native.c:icp_native_init_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302461728,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/powernv/opal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302477172,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/powernv/opal-fadump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan",
        "arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302480540,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/powernv/pci-ioda.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283140520,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/pseries/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs",
        "arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs",
        "arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs",
        "arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size",
        "arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size",
        "arch/powerpc/platforms/pseries/setup.c:of_pci_set_vf_bar_size",
        "arch/powerpc/platforms/pseries/setup.c:pseries_get_iov_fw_value",
        "arch/powerpc/platforms/pseries/setup.c:pseries_get_iov_fw_value"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283152096,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/pseries/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/iommu.c:enable_ddw",
        "arch/powerpc/platforms/pseries/iommu.c:enable_ddw"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283167840,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/pseries/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283217328,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/pseries/vio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/vio.c:vio_find_node",
        "arch/powerpc/platforms/pseries/vio.c:vio_register_device_node",
        "arch/powerpc/platforms/pseries/vio.c:vio_register_device_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302499364,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "arch/powerpc/platforms/pseries/rtas-fadump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/tty/hvc/hvc_vio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_vio.c:hvc_vio_init_early"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292060612,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/iommu/of_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/of_iommu.c:of_get_dma_window",
        "drivers/iommu/of_iommu.c:of_get_dma_window"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295025984,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:__of_find_n_match_cpu_property"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295046048,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/property.c:of_property_read_variable_u64_array",
        "drivers/of/property.c:of_property_read_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302850948,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:dt_mem_next_cell"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302856996,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt_address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_translate",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295077580,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_get_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_get_pci_address",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_default_translate",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302859536,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/of_reserved_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 of_read_number(const __be32 * cell, int size)
```

```json
{
  "name": "of_read_number",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278069760,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:arch_find_n_match_cpu_physical_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278085398,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/property.c:of_property_read_variable_u64_array",
        "drivers/of/property.c:of_property_read_u64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278093808,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:dt_mem_next_cell"
      ]
    },
    {
      "addr": 18446743936278094026,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/fdt_address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_translate",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map",
        "drivers/of/fdt_address.c:fdt_bus_default_map"
      ]
    },
    {
      "addr": 18446743936278101034,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/address.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_dma_get_range",
        "drivers/of/address.c:of_get_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:__of_translate_address",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_bus_isa_map",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_get_pci_address",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_pci_map",
        "drivers/of/address.c:of_bus_default_translate",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map",
        "drivers/of/address.c:of_bus_default_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270845482,
      "name": "of_read_number",
      "external": false,
      "loc": "include/linux/of.h:234",
      "file": "drivers/of/of_reserved_mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278093808,
      "name": "of_read_number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446743936278094026,
      "name": "of_read_number",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
u64 of_read_number(const __be32 * cell, int size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
u64 of_read_number(const __be32 * cell, int size)
```
</details>
</li>
</ul>
