# Function: <code>omap_ctrl_writel</code>

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
void omap_ctrl_writel(u32 val, u16 offset)
```

```json
{
  "name": "omap_ctrl_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224590820,
      "name": "omap_ctrl_writel",
      "external": true,
      "loc": "arch/arm/mach-omap2/control.c:197",
      "file": "arch/arm/mach-omap2/control.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/control.c:am43xx_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_init",
        "arch/arm/mach-omap2/control.c:omap3_ctrl_save_padconf",
        "arch/arm/mach-omap2/control.c:omap3630_ctrl_disable_rta",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap3_control_restore_context",
        "arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_mode",
        "arch/arm/mach-omap2/control.c:omap_ctrl_write_dsp_boot_addr",
        "arch/arm/mach-omap2/control.c:omap_ctrl_writeb"
      ],
      "caller_func": [
        "arch/arm/mach-omap2/pm34xx.c:omap_sram_idle",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_logicpd_torpedo_init",
        "arch/arm/mach-omap2/pdata-quirks.c:am35xx_emac_reset",
        "arch/arm/mach-omap2/pdata-quirks.c:am35xx_disable_emac_int",
        "arch/arm/mach-omap2/pdata-quirks.c:am35xx_enable_emac_int",
        "arch/arm/mach-omap2/pdata-quirks.c:hsmmc2_internal_input_clk",
        "arch/arm/mach-omap2/omap_phy_internal.c:am35x_set_mode",
        "arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_clear_irq",
        "arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_phy_power",
        "arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_phy_power",
        "arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_reset",
        "arch/arm/mach-omap2/omap_phy_internal.c:am35x_musb_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224588788,
      "name": "omap_ctrl_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void omap_ctrl_writel(u32 val, u16 offset)
```
</details>
</li>
</ul>
