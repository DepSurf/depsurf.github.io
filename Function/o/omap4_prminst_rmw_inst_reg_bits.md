# Function: <code>omap4_prminst_rmw_inst_reg_bits</code>

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
u32 omap4_prminst_rmw_inst_reg_bits(u32 mask, u32 bits, u8 part, s16 inst, u16 idx)
```

```json
{
  "name": "omap4_prminst_rmw_inst_reg_bits",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224645792,
      "name": "omap4_prminst_rmw_inst_reg_bits",
      "external": true,
      "loc": "arch/arm/mach-omap2/prminst44xx.c:76",
      "file": "arch/arm/mach-omap2/prminst44xx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_mem_retst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_mem_onst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_logic_retst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_clear_all_prev_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_lowpwrstchange",
        "arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_next_pwrst",
        "arch/arm/mach-omap2/prm44xx.c:omap4_prm_vcvp_rmw",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_deassert_hardreset",
        "arch/arm/mach-omap2/prminst44xx.c:omap4_prminst_assert_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224645416,
      "name": "omap4_prminst_rmw_inst_reg_bits",
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
u32 omap4_prminst_rmw_inst_reg_bits(u32 mask, u32 bits, u8 part, s16 inst, u16 idx)
```
</details>
</li>
</ul>
