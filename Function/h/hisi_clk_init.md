# Function: <code>hisi_clk_init</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct hisi_clock_data * hisi_clk_init(struct device_node * np, int nr_clks)
```

```json
{
  "name": "hisi_clk_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497823984,
      "name": "hisi_clk_init",
      "external": true,
      "loc": "drivers/clk/hisilicon/clk.c:58",
      "file": "drivers/clk/hisilicon/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_early_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media2_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media1_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_acpu_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_ao_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497823984,
      "name": "hisi_clk_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct hisi_clock_data * hisi_clk_init(struct device_node * np, int nr_clks)
```

```json
{
  "name": "hisi_clk_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230628672,
      "name": "hisi_clk_init",
      "external": true,
      "loc": "drivers/clk/hisilicon/clk.c:58",
      "file": "drivers/clk/hisilicon/clk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hi3620.c:hi3620_clk_init",
        "drivers/clk/hisilicon/clk-hip04.c:hip04_clk_init",
        "drivers/clk/hisilicon/clk-hix5hd2.c:hix5hd2_clk_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_early_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media2_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media1_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_acpu_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_ao_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230628672,
      "name": "hisi_clk_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct hisi_clock_data * hisi_clk_init(struct device_node * np, int nr_clks)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct hisi_clock_data * hisi_clk_init(struct device_node * np, int nr_clks)
```
</details>
</li>
</ul>
