# Function: <code>of_find_node_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_name",
      "external": false,
      "loc": "include/linux/of.h:401",
      "file": "drivers/mfd/twl4030-audio.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_name",
      "external": false,
      "loc": "include/linux/of.h:425",
      "file": "drivers/mfd/twl4030-audio.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_name",
      "external": false,
      "loc": "include/linux/of.h:545",
      "file": "drivers/mfd/twl4030-audio.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_find_node_by_name",
      "external": false,
      "loc": "include/linux/of.h:563",
      "file": "drivers/mfd/twl4030-audio.c",
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
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501598624,
      "name": "of_find_node_by_name",
      "external": true,
      "loc": "drivers/of/base.c:997",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones",
        "drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register",
        "drivers/firmware/arm_sdei.c:sdei_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501598624,
      "name": "of_find_node_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234123300,
      "name": "of_find_node_by_name",
      "external": true,
      "loc": "drivers/of/base.c:997",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init",
        "arch/arm/mach-omap2/omap_hwmod_3xxx_data.c:omap3xxx_hwmod_init",
        "drivers/clk/mvebu/common.c:kirkwood_fix_sscg_deviation",
        "drivers/clk/ti/clk.c:ti_dt_clocks_register",
        "drivers/clk/ti/clk-814x.c:dm814x_adpll_early_init",
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones",
        "drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe",
        "drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234123300,
      "name": "of_find_node_by_name",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295017744,
      "name": "of_find_node_by_name",
      "external": true,
      "loc": "drivers/of/base.c:997",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:check_legacy_ioport",
        "arch/powerpc/kernel/rtas.c:rtas_initialize",
        "arch/powerpc/kernel/rtas-proc.c:proc_rtas_init",
        "arch/powerpc/platforms/powernv/setup.c:pnv_setup_arch",
        "arch/powerpc/platforms/pseries/vio.c:vio_cmo_num_OF_devs",
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones",
        "drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295017744,
      "name": "of_find_node_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```

```json
{
  "name": "of_find_node_by_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278065344,
      "name": "of_find_node_by_name",
      "external": true,
      "loc": "drivers/of/base.c:997",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/of-thermal.c:of_parse_thermal_zones",
        "drivers/thermal/of-thermal.c:thermal_zone_of_sensor_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278065344,
      "name": "of_find_node_by_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_find_node_by_name(struct device_node * from, const char * name)
```
</details>
</li>
</ul>
