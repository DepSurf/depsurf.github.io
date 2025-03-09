# Struct: <code>omap3_cm_regs</code>

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
struct omap3_cm_regs {
    u32 iva2_cm_clksel1;
    u32 iva2_cm_clksel2;
    u32 cm_sysconfig;
    u32 sgx_cm_clksel;
    u32 dss_cm_clksel;
    u32 cam_cm_clksel;
    u32 per_cm_clksel;
    u32 emu_cm_clksel;
    u32 emu_cm_clkstctrl;
    u32 pll_cm_autoidle;
    u32 pll_cm_autoidle2;
    u32 pll_cm_clksel4;
    u32 pll_cm_clksel5;
    u32 pll_cm_clken2;
    u32 cm_polctrl;
    u32 iva2_cm_fclken;
    u32 iva2_cm_clken_pll;
    u32 core_cm_fclken1;
    u32 core_cm_fclken3;
    u32 sgx_cm_fclken;
    u32 wkup_cm_fclken;
    u32 dss_cm_fclken;
    u32 cam_cm_fclken;
    u32 per_cm_fclken;
    u32 usbhost_cm_fclken;
    u32 core_cm_iclken1;
    u32 core_cm_iclken2;
    u32 core_cm_iclken3;
    u32 sgx_cm_iclken;
    u32 wkup_cm_iclken;
    u32 dss_cm_iclken;
    u32 cam_cm_iclken;
    u32 per_cm_iclken;
    u32 usbhost_cm_iclken;
    u32 iva2_cm_autoidle2;
    u32 mpu_cm_autoidle2;
    u32 iva2_cm_clkstctrl;
    u32 mpu_cm_clkstctrl;
    u32 core_cm_clkstctrl;
    u32 sgx_cm_clkstctrl;
    u32 dss_cm_clkstctrl;
    u32 cam_cm_clkstctrl;
    u32 per_cm_clkstctrl;
    u32 neon_cm_clkstctrl;
    u32 usbhost_cm_clkstctrl;
    u32 core_cm_autoidle1;
    u32 core_cm_autoidle2;
    u32 core_cm_autoidle3;
    u32 wkup_cm_autoidle;
    u32 dss_cm_autoidle;
    u32 cam_cm_autoidle;
    u32 per_cm_autoidle;
    u32 usbhost_cm_autoidle;
    u32 sgx_cm_sleepdep;
    u32 dss_cm_sleepdep;
    u32 cam_cm_sleepdep;
    u32 per_cm_sleepdep;
    u32 usbhost_cm_sleepdep;
    u32 cm_clkout_ctrl;
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
struct omap3_cm_regs {
    u32 iva2_cm_clksel1;
    u32 iva2_cm_clksel2;
    u32 cm_sysconfig;
    u32 sgx_cm_clksel;
    u32 dss_cm_clksel;
    u32 cam_cm_clksel;
    u32 per_cm_clksel;
    u32 emu_cm_clksel;
    u32 emu_cm_clkstctrl;
    u32 pll_cm_autoidle;
    u32 pll_cm_autoidle2;
    u32 pll_cm_clksel4;
    u32 pll_cm_clksel5;
    u32 pll_cm_clken2;
    u32 cm_polctrl;
    u32 iva2_cm_fclken;
    u32 iva2_cm_clken_pll;
    u32 core_cm_fclken1;
    u32 core_cm_fclken3;
    u32 sgx_cm_fclken;
    u32 wkup_cm_fclken;
    u32 dss_cm_fclken;
    u32 cam_cm_fclken;
    u32 per_cm_fclken;
    u32 usbhost_cm_fclken;
    u32 core_cm_iclken1;
    u32 core_cm_iclken2;
    u32 core_cm_iclken3;
    u32 sgx_cm_iclken;
    u32 wkup_cm_iclken;
    u32 dss_cm_iclken;
    u32 cam_cm_iclken;
    u32 per_cm_iclken;
    u32 usbhost_cm_iclken;
    u32 iva2_cm_autoidle2;
    u32 mpu_cm_autoidle2;
    u32 iva2_cm_clkstctrl;
    u32 mpu_cm_clkstctrl;
    u32 core_cm_clkstctrl;
    u32 sgx_cm_clkstctrl;
    u32 dss_cm_clkstctrl;
    u32 cam_cm_clkstctrl;
    u32 per_cm_clkstctrl;
    u32 neon_cm_clkstctrl;
    u32 usbhost_cm_clkstctrl;
    u32 core_cm_autoidle1;
    u32 core_cm_autoidle2;
    u32 core_cm_autoidle3;
    u32 wkup_cm_autoidle;
    u32 dss_cm_autoidle;
    u32 cam_cm_autoidle;
    u32 per_cm_autoidle;
    u32 usbhost_cm_autoidle;
    u32 sgx_cm_sleepdep;
    u32 dss_cm_sleepdep;
    u32 cam_cm_sleepdep;
    u32 per_cm_sleepdep;
    u32 usbhost_cm_sleepdep;
    u32 cm_clkout_ctrl;
}
```
</details>
</li>
</ul>
