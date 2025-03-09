# Function: <code>of_translate_address</code>

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
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```

```json
{
  "name": "of_translate_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501639568,
      "name": "of_translate_address",
      "external": true,
      "loc": "drivers/of/address.c:664",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/clk/mvebu/armada_ap_cp_helper.c:ap_cp_unique_name",
        "drivers/of/platform.c:of_device_make_bus_id",
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501639568,
      "name": "of_translate_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```

```json
{
  "name": "of_translate_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234159440,
      "name": "of_translate_address",
      "external": true,
      "loc": "drivers/of/address.c:664",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/exynos.c:exynos_sysram_init",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_parse_module_range",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "drivers/irqchip/irq-gic-v3-mbi.c:mbi_init",
        "drivers/bus/ti-sysc.c:sysc_map_and_check_registers",
        "drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/of/platform.c:of_device_make_bus_id",
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234159440,
      "name": "of_translate_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```

```json
{
  "name": "of_translate_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295075104,
      "name": "of_translate_address",
      "external": true,
      "loc": "drivers/of/address.c:664",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "arch/powerpc/kernel/isa-bridge.c:isa_bridge_init_non_pci",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb",
        "drivers/video/fbdev/offb.c:offb_init_nodriver",
        "drivers/video/fbdev/offb.c:offb_init_fb",
        "drivers/video/fbdev/offb.c:offb_map_reg",
        "drivers/of/platform.c:of_device_alloc",
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295075104,
      "name": "of_translate_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```

```json
{
  "name": "of_translate_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278099316,
      "name": "of_translate_address",
      "external": true,
      "loc": "drivers/of/address.c:664",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:of_device_alloc",
        "drivers/of/address.c:__of_address_to_resource",
        "drivers/of/address.c:of_pci_range_parser_one",
        "drivers/of/address.c:of_pci_range_parser_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278099316,
      "name": "of_translate_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
u64 of_translate_address(struct device_node * dev, const __be32 * in_addr)
```
</details>
</li>
</ul>
