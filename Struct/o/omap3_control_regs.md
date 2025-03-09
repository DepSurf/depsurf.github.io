# Struct: <code>omap3_control_regs</code>

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
struct omap3_control_regs {
    u32 sysconfig;
    u32 devconf0;
    u32 mem_dftrw0;
    u32 mem_dftrw1;
    u32 msuspendmux_0;
    u32 msuspendmux_1;
    u32 msuspendmux_2;
    u32 msuspendmux_3;
    u32 msuspendmux_4;
    u32 msuspendmux_5;
    u32 sec_ctrl;
    u32 devconf1;
    u32 csirxfe;
    u32 iva2_bootaddr;
    u32 iva2_bootmod;
    u32 wkup_ctrl;
    u32 debobs_0;
    u32 debobs_1;
    u32 debobs_2;
    u32 debobs_3;
    u32 debobs_4;
    u32 debobs_5;
    u32 debobs_6;
    u32 debobs_7;
    u32 debobs_8;
    u32 prog_io0;
    u32 prog_io1;
    u32 dss_dpll_spreading;
    u32 core_dpll_spreading;
    u32 per_dpll_spreading;
    u32 usbhost_dpll_spreading;
    u32 pbias_lite;
    u32 temp_sensor;
    u32 sramldo4;
    u32 sramldo5;
    u32 csi;
    u32 padconf_sys_nirq;
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
struct omap3_control_regs {
    u32 sysconfig;
    u32 devconf0;
    u32 mem_dftrw0;
    u32 mem_dftrw1;
    u32 msuspendmux_0;
    u32 msuspendmux_1;
    u32 msuspendmux_2;
    u32 msuspendmux_3;
    u32 msuspendmux_4;
    u32 msuspendmux_5;
    u32 sec_ctrl;
    u32 devconf1;
    u32 csirxfe;
    u32 iva2_bootaddr;
    u32 iva2_bootmod;
    u32 wkup_ctrl;
    u32 debobs_0;
    u32 debobs_1;
    u32 debobs_2;
    u32 debobs_3;
    u32 debobs_4;
    u32 debobs_5;
    u32 debobs_6;
    u32 debobs_7;
    u32 debobs_8;
    u32 prog_io0;
    u32 prog_io1;
    u32 dss_dpll_spreading;
    u32 core_dpll_spreading;
    u32 per_dpll_spreading;
    u32 usbhost_dpll_spreading;
    u32 pbias_lite;
    u32 temp_sensor;
    u32 sramldo4;
    u32 sramldo5;
    u32 csi;
    u32 padconf_sys_nirq;
}
```
</details>
</li>
</ul>
