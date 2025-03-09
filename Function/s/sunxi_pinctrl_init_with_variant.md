# Function: <code>sunxi_pinctrl_init_with_variant</code>

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
int sunxi_pinctrl_init_with_variant(struct platform_device * pdev, const struct sunxi_pinctrl_desc * desc, long unsigned int variant)
```

```json
{
  "name": "sunxi_pinctrl_init_with_variant",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496669832,
      "name": "sunxi_pinctrl_init_with_variant",
      "external": true,
      "loc": "drivers/pinctrl/sunxi/pinctrl-sunxi.c:1379",
      "file": "drivers/pinctrl/sunxi/pinctrl-sunxi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sunxi/pinctrl-sun4i-a10.c:sun4i_a10_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun5i.c:sun5i_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun6i-a31.c:sun6i_a31_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a23.c:sun8i_a23_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a33.c:sun8i_a33_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-a64.c:a64_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-a64-r.c:sun50i_a64_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a83t.c:sun8i_a83t_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-a83t-r.c:sun8i_a83t_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-h3.c:sun8i_h3_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-h3-r.c:sun8i_h3_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun8i-v3s.c:sun8i_v3s_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-h6.c:h6_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun50i-h6-r.c:sun50i_h6_r_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun9i-a80.c:sun9i_a80_pinctrl_probe",
        "drivers/pinctrl/sunxi/pinctrl-sun9i-a80-r.c:sun9i_a80_r_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496669832,
      "name": "sunxi_pinctrl_init_with_variant",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1892
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
int sunxi_pinctrl_init_with_variant(struct platform_device * pdev, const struct sunxi_pinctrl_desc * desc, long unsigned int variant)
```
</details>
</li>
</ul>
