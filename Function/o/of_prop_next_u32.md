# Function: <code>of_prop_next_u32</code>

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
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```

```json
{
  "name": "of_prop_next_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501617952,
      "name": "of_prop_next_u32",
      "external": true,
      "loc": "drivers/of/property.c:483",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/clk/clk.c:of_clk_detect_critical",
        "drivers/clk/clk.c:of_clk_detect_critical",
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup",
        "drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup",
        "drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init",
        "drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/tty/sysrq.c:sysrq_toggle_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501617952,
      "name": "of_prop_next_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```

```json
{
  "name": "of_prop_next_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234140692,
      "name": "of_prop_next_u32",
      "external": true,
      "loc": "drivers/of/property.c:483",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/bus/ti-sysc.c:sysc_init_idlemode",
        "drivers/bus/ti-sysc.c:sysc_init_idlemode",
        "drivers/clk/clk.c:of_clk_detect_critical",
        "drivers/clk/clk.c:of_clk_detect_critical",
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/tty/sysrq.c:sysrq_toggle_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234140692,
      "name": "of_prop_next_u32",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```

```json
{
  "name": "of_prop_next_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295045136,
      "name": "of_prop_next_u32",
      "external": true,
      "loc": "drivers/of/property.c:483",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xive/native.c:xive_native_init",
        "arch/powerpc/sysdev/xive/native.c:xive_native_init",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init",
        "arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell",
        "arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell",
        "arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell",
        "arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell",
        "arch/powerpc/platforms/pseries/of_helpers.c:of_read_drc_info_cell",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/tty/sysrq.c:sysrq_toggle_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295045136,
      "name": "of_prop_next_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```

```json
{
  "name": "of_prop_next_u32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278080700,
      "name": "of_prop_next_u32",
      "external": true,
      "loc": "drivers/of/property.c:483",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:of_clk_detect_critical",
        "drivers/clk/clk.c:of_clk_detect_critical",
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/clk/clk.c:of_clk_get_parent_name",
        "drivers/tty/sysrq.c:sysrq_toggle_support",
        "drivers/tty/sysrq.c:sysrq_toggle_support"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278080700,
      "name": "of_prop_next_u32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const __be32 * of_prop_next_u32(struct property * prop, const __be32 * cur, u32 * pu)
```
</details>
</li>
</ul>
