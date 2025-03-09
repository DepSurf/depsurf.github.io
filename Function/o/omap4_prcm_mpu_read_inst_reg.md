# Function: <code>omap4_prcm_mpu_read_inst_reg</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u32 omap4_prcm_mpu_read_inst_reg(s16 inst, u16 reg)
```

```json
{
  "name": "omap4_prcm_mpu_read_inst_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224645056,
      "name": "omap4_prcm_mpu_read_inst_reg",
      "external": true,
      "loc": "arch/arm/mach-omap2/prcm_mpu44xx.c:28",
      "file": "arch/arm/mach-omap2/prcm_mpu44xx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prcm_mpu44xx.c:omap4_prcm_mpu_rmw_inst_reg_bits"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224644956,
      "name": "omap4_prcm_mpu_read_inst_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
u32 omap4_prcm_mpu_read_inst_reg(s16 inst, u16 reg)
```
</details>
</li>
</ul>
