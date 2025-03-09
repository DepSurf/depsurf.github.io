# Function: <code>samsung_cmu_register_one</code>

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
struct samsung_clk_provider * samsung_cmu_register_one(struct device_node * np, const struct samsung_cmu_info * cmu)
```

```json
{
  "name": "samsung_cmu_register_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243788616,
      "name": "samsung_cmu_register_one",
      "external": true,
      "loc": "drivers/clk/samsung/clk.c:346",
      "file": "drivers/clk/samsung/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_top_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_peri_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_mif_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_mfc_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_kfc_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_isp_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_gscl_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_g3d_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_g2d_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_fsys_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_egl_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_disp_init",
        "drivers/clk/samsung/clk-exynos5260.c:exynos5260_clk_aud_init",
        "drivers/clk/samsung/clk-exynos5410.c:exynos5410_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243788616,
      "name": "samsung_cmu_register_one",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct samsung_clk_provider * samsung_cmu_register_one(struct device_node * np, const struct samsung_cmu_info * cmu)
```
</details>
</li>
</ul>
