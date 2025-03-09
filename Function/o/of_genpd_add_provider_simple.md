# Function: <code>of_genpd_add_provider_simple</code>

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
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```

```json
{
  "name": "of_genpd_add_provider_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499099704,
      "name": "of_genpd_add_provider_simple",
      "external": true,
      "loc": "drivers/base/power/domain.c:2028",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe",
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe",
        "drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499099704,
      "name": "of_genpd_add_provider_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```

```json
{
  "name": "of_genpd_add_provider_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231652864,
      "name": "of_genpd_add_provider_simple",
      "external": true,
      "loc": "drivers/base/power/domain.c:2028",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_add_clk_domain",
        "drivers/soc/dove/pmu.c:dove_init_pmu",
        "drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe",
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe",
        "drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe",
        "drivers/soc/renesas/rmobile-sysc.c:rmobile_add_pm_domains",
        "drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain",
        "drivers/soc/tegra/pmc.c:tegra_powergate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231652864,
      "name": "of_genpd_add_provider_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```

```json
{
  "name": "of_genpd_add_provider_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292295376,
      "name": "of_genpd_add_provider_simple",
      "external": true,
      "loc": "drivers/base/power/domain.c:2028",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292295376,
      "name": "of_genpd_add_provider_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```

```json
{
  "name": "of_genpd_add_provider_simple",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276426188,
      "name": "of_genpd_add_provider_simple",
      "external": true,
      "loc": "drivers/base/power/domain.c:2028",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276426188,
      "name": "of_genpd_add_provider_simple",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_genpd_add_provider_simple(struct device_node * np, struct generic_pm_domain * genpd)
```
</details>
</li>
</ul>
