# Function: <code>of_get_address</code>

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
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501637248,
      "name": "of_get_address",
      "external": true,
      "loc": "drivers/of/address.c:715",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show",
        "drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_show",
        "drivers/of/address.c:of_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501637248,
      "name": "of_get_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234155652,
      "name": "of_get_address",
      "external": true,
      "loc": "drivers/of/address.c:715",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/exynos.c:exynos_sysram_init",
        "arch/arm/mach-exynos/firmware.c:exynos_secure_firmware_available",
        "arch/arm/mach-omap2/omap_hwmod.c:omap_hwmod_init",
        "drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init",
        "drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup",
        "drivers/of/address.c:of_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234155652,
      "name": "of_get_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295069808,
      "name": "of_get_address",
      "external": true,
      "loc": "drivers/of/address.c:715",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports",
        "drivers/video/fbdev/offb.c:offb_init_nodriver",
        "drivers/video/fbdev/offb.c:offb_map_reg",
        "drivers/of/address.c:of_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295069808,
      "name": "of_get_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```

```json
{
  "name": "of_get_address",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278097266,
      "name": "of_get_address",
      "external": true,
      "loc": "drivers/of/address.c:715",
      "file": "drivers/of/address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/address.c:of_address_to_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278097266,
      "name": "of_get_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const __be32 * of_get_address(struct device_node * dev, int index, u64 * size, unsigned int * flags)
```
</details>
</li>
</ul>
