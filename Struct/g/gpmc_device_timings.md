# Struct: <code>gpmc_device_timings</code>

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
struct gpmc_device_timings {
    u32 t_ceasu;
    u32 t_avdasu;
    u32 t_avdp_r;
    u32 t_avdp_w;
    u32 t_aavdh;
    u32 t_oeasu;
    u32 t_aa;
    u32 t_iaa;
    u32 t_oe;
    u32 t_ce;
    u32 t_rd_cycle;
    u32 t_cez_r;
    u32 t_cez_w;
    u32 t_oez;
    u32 t_weasu;
    u32 t_wpl;
    u32 t_wph;
    u32 t_wr_cycle;
    u32 clk;
    u32 t_bacc;
    u32 t_ces;
    u32 t_avds;
    u32 t_avdh;
    u32 t_ach;
    u32 t_rdyo;
    u32 t_ce_rdyz;
    u32 t_ce_avd;
    u8 cyc_aavdh_oe;
    u8 cyc_aavdh_we;
    u8 cyc_oe;
    u8 cyc_wpl;
    u32 cyc_iaa;
    bool ce_xdelay;
    bool avd_xdelay;
    bool oe_xdelay;
    bool we_xdelay;
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
struct gpmc_device_timings {
    u32 t_ceasu;
    u32 t_avdasu;
    u32 t_avdp_r;
    u32 t_avdp_w;
    u32 t_aavdh;
    u32 t_oeasu;
    u32 t_aa;
    u32 t_iaa;
    u32 t_oe;
    u32 t_ce;
    u32 t_rd_cycle;
    u32 t_cez_r;
    u32 t_cez_w;
    u32 t_oez;
    u32 t_weasu;
    u32 t_wpl;
    u32 t_wph;
    u32 t_wr_cycle;
    u32 clk;
    u32 t_bacc;
    u32 t_ces;
    u32 t_avds;
    u32 t_avdh;
    u32 t_ach;
    u32 t_rdyo;
    u32 t_ce_rdyz;
    u32 t_ce_avd;
    u8 cyc_aavdh_oe;
    u8 cyc_aavdh_we;
    u8 cyc_oe;
    u8 cyc_wpl;
    u32 cyc_iaa;
    bool ce_xdelay;
    bool avd_xdelay;
    bool oe_xdelay;
    bool we_xdelay;
}
```
</details>
</li>
</ul>
