# Function: <code>of_clk_get_from_provider</code>

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
struct clk * of_clk_get_from_provider(struct of_phandle_args * clkspec)
```

```json
{
  "name": "of_clk_get_from_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497753384,
      "name": "of_clk_get_from_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4583",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497753384,
      "name": "of_clk_get_from_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct clk * of_clk_get_from_provider(struct of_phandle_args * clkspec)
```

```json
{
  "name": "of_clk_get_from_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230577584,
      "name": "of_clk_get_from_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4583",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/clk/imx/clk.c:imx_obtain_fixed_clock_from_dt",
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_attach_dev",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_attach_dev",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_attach_dev",
        "drivers/clk/ti/clk.c:ti_clk_add_aliases",
        "drivers/clk/ti/clk.c:ti_dt_clocks_register",
        "drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230577584,
      "name": "of_clk_get_from_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clk * of_clk_get_from_provider(struct of_phandle_args * clkspec)
```

```json
{
  "name": "of_clk_get_from_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275898526,
      "name": "of_clk_get_from_provider",
      "external": true,
      "loc": "drivers/clk/clk.c:4583",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_get_parent_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275898526,
      "name": "of_clk_get_from_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct clk * of_clk_get_from_provider(struct of_phandle_args * clkspec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct clk * of_clk_get_from_provider(struct of_phandle_args * clkspec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct clk * of_clk_get_from_provider(struct of_phandle_args * clkspec)
```
</details>
</li>
</ul>
