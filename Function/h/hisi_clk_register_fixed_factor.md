# Function: <code>hisi_clk_register_fixed_factor</code>

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
int hisi_clk_register_fixed_factor(const struct hisi_fixed_factor_clock * clks, int nums, struct hisi_clock_data * data)
```

```json
{
  "name": "hisi_clk_register_fixed_factor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497822424,
      "name": "hisi_clk_register_fixed_factor",
      "external": true,
      "loc": "drivers/clk/hisilicon/clk.c:120",
      "file": "drivers/clk/hisilicon/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_ao_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497822424,
      "name": "hisi_clk_register_fixed_factor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int hisi_clk_register_fixed_factor(const struct hisi_fixed_factor_clock * clks, int nums, struct hisi_clock_data * data)
```

```json
{
  "name": "hisi_clk_register_fixed_factor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230627296,
      "name": "hisi_clk_register_fixed_factor",
      "external": true,
      "loc": "drivers/clk/hisilicon/clk.c:120",
      "file": "drivers/clk/hisilicon/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hi3620.c:hi3620_clk_init",
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_iomcu_init",
        "drivers/clk/hisilicon/clk-hi3670.c:hi3670_clk_crgctrl_init",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_ao_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230627296,
      "name": "hisi_clk_register_fixed_factor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int hisi_clk_register_fixed_factor(const struct hisi_fixed_factor_clock * clks, int nums, struct hisi_clock_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int hisi_clk_register_fixed_factor(const struct hisi_fixed_factor_clock * clks, int nums, struct hisi_clock_data * data)
```
</details>
</li>
</ul>
