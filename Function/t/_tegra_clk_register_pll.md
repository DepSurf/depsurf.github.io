# Function: <code>_tegra_clk_register_pll</code>

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
struct clk * _tegra_clk_register_pll(struct tegra_clk_pll * pll, const char * name, const char * parent_name, long unsigned int flags, const struct clk_ops * ops)
```

```json
{
  "name": "_tegra_clk_register_pll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230726276,
      "name": "_tegra_clk_register_pll",
      "external": false,
      "loc": "drivers/clk/tegra/clk-pll.c:1829",
      "file": "drivers/clk/tegra/clk-pll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllu_tegra114",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle_tegra114",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllm",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllre",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllu",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_plle",
        "drivers/clk/tegra/clk-pll.c:tegra_clk_register_pll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230726276,
      "name": "_tegra_clk_register_pll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct clk * _tegra_clk_register_pll(struct tegra_clk_pll * pll, const char * name, const char * parent_name, long unsigned int flags, const struct clk_ops * ops)
```
</details>
</li>
</ul>
