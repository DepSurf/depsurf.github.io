# Function: <code>rockchip_clk_register_branches</code>

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
void rockchip_clk_register_branches(struct rockchip_clk_provider * ctx, struct rockchip_clk_branch * list, unsigned int nr_clk)
```

```json
{
  "name": "rockchip_clk_register_branches",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511165276,
      "name": "rockchip_clk_register_branches",
      "external": true,
      "loc": "drivers/clk/rockchip/clk.c:437",
      "file": "drivers/clk/rockchip/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/rockchip/clk-px30.c:px30_pmu_clk_init",
        "drivers/clk/rockchip/clk-px30.c:px30_clk_init",
        "drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init",
        "drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3128_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3126_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3066a_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188_common_clk_init",
        "drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init",
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init",
        "drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init",
        "drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init",
        "drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_pmu_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511165276,
      "name": "rockchip_clk_register_branches",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 2404
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
void rockchip_clk_register_branches(struct rockchip_clk_provider * ctx, struct rockchip_clk_branch * list, unsigned int nr_clk)
```

```json
{
  "name": "rockchip_clk_register_branches",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243779360,
      "name": "rockchip_clk_register_branches",
      "external": true,
      "loc": "drivers/clk/rockchip/clk.c:437",
      "file": "drivers/clk/rockchip/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/rockchip/clk-px30.c:px30_pmu_clk_init",
        "drivers/clk/rockchip/clk-px30.c:px30_clk_init",
        "drivers/clk/rockchip/clk-rv1108.c:rv1108_clk_init",
        "drivers/clk/rockchip/clk-rk3036.c:rk3036_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3128_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3126_clk_init",
        "drivers/clk/rockchip/clk-rk3128.c:rk3128_common_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3066a_clk_init",
        "drivers/clk/rockchip/clk-rk3188.c:rk3188_common_clk_init",
        "drivers/clk/rockchip/clk-rk3228.c:rk3228_clk_init",
        "drivers/clk/rockchip/clk-rk3288.c:rk3288_clk_init",
        "drivers/clk/rockchip/clk-rk3308.c:rk3308_clk_init",
        "drivers/clk/rockchip/clk-rk3328.c:rk3328_clk_init",
        "drivers/clk/rockchip/clk-rk3368.c:rk3368_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_pmu_clk_init",
        "drivers/clk/rockchip/clk-rk3399.c:rk3399_clk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243779360,
      "name": "rockchip_clk_register_branches",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 2592
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
void rockchip_clk_register_branches(struct rockchip_clk_provider * ctx, struct rockchip_clk_branch * list, unsigned int nr_clk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void rockchip_clk_register_branches(struct rockchip_clk_provider * ctx, struct rockchip_clk_branch * list, unsigned int nr_clk)
```
</details>
</li>
</ul>
