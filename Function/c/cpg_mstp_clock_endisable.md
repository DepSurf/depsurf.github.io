# Function: <code>cpg_mstp_clock_endisable</code>

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
int cpg_mstp_clock_endisable(struct clk_hw * hw, bool enable)
```

```json
{
  "name": "cpg_mstp_clock_endisable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497938904,
      "name": "cpg_mstp_clock_endisable",
      "external": false,
      "loc": "drivers/clk/renesas/renesas-cpg-mssr.c:164",
      "file": "drivers/clk/renesas/renesas-cpg-mssr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_disable",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497938904,
      "name": "cpg_mstp_clock_endisable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int cpg_mstp_clock_endisable(struct clk_hw * hw, bool enable)
```

```json
{
  "name": "cpg_mstp_clock_endisable",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230683388,
      "name": "cpg_mstp_clock_endisable",
      "external": false,
      "loc": "drivers/clk/renesas/renesas-cpg-mssr.c:164",
      "file": "drivers/clk/renesas/renesas-cpg-mssr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_disable",
        "drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_enable"
      ]
    },
    {
      "addr": 3230685688,
      "name": "cpg_mstp_clock_endisable",
      "external": false,
      "loc": "drivers/clk/renesas/clk-mstp.c:75",
      "file": "drivers/clk/renesas/clk-mstp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_disable",
        "drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230683388,
      "name": "cpg_mstp_clock_endisable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 3230685688,
      "name": "cpg_mstp_clock_endisable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int cpg_mstp_clock_endisable(struct clk_hw * hw, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int cpg_mstp_clock_endisable(struct clk_hw * hw, bool enable)
```
</details>
</li>
</ul>
