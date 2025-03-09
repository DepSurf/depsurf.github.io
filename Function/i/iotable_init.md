# Function: <code>iotable_init</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void iotable_init(struct map_desc * io_desc, int nr)
```

```json
{
  "name": "iotable_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243281704,
      "name": "iotable_init",
      "external": true,
      "loc": "arch/arm/mm/mmu.c:990",
      "file": "arch/arm/mm/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/bios32.c:pci_map_io_early",
        "arch/arm/mm/dma-mapping.c:dma_contiguous_remap",
        "arch/arm/mach-exynos/exynos.c:exynos_fdt_map_chipid",
        "arch/arm/mach-hisi/hisilicon.c:hi3620_map_io",
        "arch/arm/mach-imx/platsmp.c:imx_scu_map_io",
        "arch/arm/mach-omap2/io.c:ti81xx_map_io",
        "arch/arm/mach-omap2/io.c:dra7xx_map_io",
        "arch/arm/mach-omap2/io.c:omap4_map_io",
        "arch/arm/mach-omap2/io.c:am33xx_map_io",
        "arch/arm/mach-omap2/io.c:omap3_map_io",
        "arch/arm/mach-omap2/omap4-common.c:omap_barriers_init",
        "arch/arm/mach-shmobile/setup-sh73a0.c:sh73a0_map_io",
        "arch/arm/mach-shmobile/setup-r8a7779.c:r8a7779_map_io",
        "arch/arm/mach-tegra/io.c:tegra_map_common_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243281704,
      "name": "iotable_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void iotable_init(struct map_desc * io_desc, int nr)
```
</details>
</li>
</ul>
