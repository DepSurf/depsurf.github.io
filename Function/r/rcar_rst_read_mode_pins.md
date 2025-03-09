# Function: <code>rcar_rst_read_mode_pins</code>

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
int rcar_rst_read_mode_pins(u32 * mode)
```

```json
{
  "name": "rcar_rst_read_mode_pins",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511197160,
      "name": "rcar_rst_read_mode_pins",
      "external": true,
      "loc": "drivers/soc/renesas/rcar-rst.c:110",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/r8a774a1-cpg-mssr.c:r8a774a1_cpg_mssr_init",
        "drivers/clk/renesas/r8a774c0-cpg-mssr.c:r8a774c0_cpg_mssr_init",
        "drivers/clk/renesas/r8a7795-cpg-mssr.c:r8a7795_cpg_mssr_init",
        "drivers/clk/renesas/r8a7796-cpg-mssr.c:r8a7796_cpg_mssr_init",
        "drivers/clk/renesas/r8a77965-cpg-mssr.c:r8a77965_cpg_mssr_init",
        "drivers/clk/renesas/r8a77970-cpg-mssr.c:r8a77970_cpg_mssr_init",
        "drivers/clk/renesas/r8a77980-cpg-mssr.c:r8a77980_cpg_mssr_init",
        "drivers/clk/renesas/r8a77990-cpg-mssr.c:r8a77990_cpg_mssr_init",
        "drivers/clk/renesas/r8a77995-cpg-mssr.c:r8a77995_cpg_mssr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511197160,
      "name": "rcar_rst_read_mode_pins",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int rcar_rst_read_mode_pins(u32 * mode)
```

```json
{
  "name": "rcar_rst_read_mode_pins",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243837972,
      "name": "rcar_rst_read_mode_pins",
      "external": true,
      "loc": "drivers/soc/renesas/rcar-rst.c:110",
      "file": "drivers/soc/renesas/rcar-rst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/r8a7743-cpg-mssr.c:r8a7743_cpg_mssr_init",
        "drivers/clk/renesas/r8a7745-cpg-mssr.c:r8a7745_cpg_mssr_init",
        "drivers/clk/renesas/r8a77470-cpg-mssr.c:r8a77470_cpg_mssr_init",
        "drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init",
        "drivers/clk/renesas/clk-r8a7779.c:r8a7779_cpg_clocks_init",
        "drivers/clk/renesas/r8a7790-cpg-mssr.c:r8a7790_cpg_mssr_init",
        "drivers/clk/renesas/r8a7791-cpg-mssr.c:r8a7791_cpg_mssr_init",
        "drivers/clk/renesas/r8a7792-cpg-mssr.c:r8a7792_cpg_mssr_init",
        "drivers/clk/renesas/r8a7794-cpg-mssr.c:r8a7794_cpg_mssr_init",
        "drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243837972,
      "name": "rcar_rst_read_mode_pins",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int rcar_rst_read_mode_pins(u32 * mode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int rcar_rst_read_mode_pins(u32 * mode)
```
</details>
</li>
</ul>
