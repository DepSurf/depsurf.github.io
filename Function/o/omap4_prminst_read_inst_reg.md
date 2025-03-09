# Function: <code>omap4_prminst_read_inst_reg</code>

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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
u32 omap4_prminst_read_inst_reg(u8 part, s16 inst, u16 idx)
```

```json
{
  "name": "omap4_prminst_read_inst_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224645988,
      "name": "omap4_prminst_read_inst_reg",
      "external": true,
      "loc": "arch/arm/mach-omap2/prminst44xx.c:58",
      "file": "arch/arm/mach-omap2/prminst44xx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_mpuss_init",
        "arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_restore_context",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_save_context",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_prev_mem_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_mem_retst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_mem_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_logic_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_next_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap44xx_prm_was_any_context_lost_old",
        "arch/arm/mach-omap2/prm44xx.c:omap4_prm_vcvp_read",
        "arch/arm/mach-omap2/prm44xx.c:omap4_prm_vp_check_txdone",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_global_warm_sw_reset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224645088,
      "name": "omap4_prminst_read_inst_reg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3224645256,
      "name": "omap4_prminst_read_inst_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
u32 omap4_prminst_read_inst_reg(u8 part, s16 inst, u16 idx)
```
</details>
</li>
</ul>
