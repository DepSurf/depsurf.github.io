# Function: <code>hisi_clk_register_gate</code>

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
int hisi_clk_register_gate(const struct hisi_gate_clock * clks, int nums, struct hisi_clock_data * data)
```

```json
{
  "name": "hisi_clk_register_gate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497823456,
      "name": "hisi_clk_register_gate",
      "external": true,
      "loc": "drivers/clk/hisilicon/clk.c:250",
      "file": "drivers/clk/hisilicon/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media1_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497823456,
      "name": "hisi_clk_register_gate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int hisi_clk_register_gate(const struct hisi_gate_clock * clks, int nums, struct hisi_clock_data * data)
```

```json
{
  "name": "hisi_clk_register_gate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230628220,
      "name": "hisi_clk_register_gate",
      "external": true,
      "loc": "drivers/clk/hisilicon/clk.c:250",
      "file": "drivers/clk/hisilicon/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hix5hd2.c:hix5hd2_clk_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_media1_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_sctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pmuctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_pctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_power_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230628220,
      "name": "hisi_clk_register_gate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int hisi_clk_register_gate(const struct hisi_gate_clock * clks, int nums, struct hisi_clock_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int hisi_clk_register_gate(const struct hisi_gate_clock * clks, int nums, struct hisi_clock_data * data)
```
</details>
</li>
</ul>
