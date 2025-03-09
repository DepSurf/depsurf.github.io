# Function: <code>of_genpd_add_provider_onecell</code>

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
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```

```json
{
  "name": "of_genpd_add_provider_onecell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499099976,
      "name": "of_genpd_add_provider_onecell",
      "external": true,
      "loc": "drivers/base/power/domain.c:2085",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/actions/owl-sps.c:owl_sps_probe",
        "drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe",
        "drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe",
        "drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe",
        "drivers/soc/qcom/rpmhpd.c:rpmhpd_probe",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe",
        "drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499099976,
      "name": "of_genpd_add_provider_onecell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```

```json
{
  "name": "of_genpd_add_provider_onecell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231653152,
      "name": "of_genpd_add_provider_onecell",
      "external": true,
      "loc": "drivers/base/power/domain.c:2085",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/actions/owl-sps.c:owl_sps_probe",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe",
        "drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe",
        "drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates",
        "drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates",
        "drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231653152,
      "name": "of_genpd_add_provider_onecell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```

```json
{
  "name": "of_genpd_add_provider_onecell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292295760,
      "name": "of_genpd_add_provider_onecell",
      "external": true,
      "loc": "drivers/base/power/domain.c:2085",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292295760,
      "name": "of_genpd_add_provider_onecell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```

```json
{
  "name": "of_genpd_add_provider_onecell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276427108,
      "name": "of_genpd_add_provider_onecell",
      "external": true,
      "loc": "drivers/base/power/domain.c:2085",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276427108,
      "name": "of_genpd_add_provider_onecell",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_genpd_add_provider_onecell(struct device_node * np, struct genpd_onecell_data * data)
```
</details>
</li>
</ul>
