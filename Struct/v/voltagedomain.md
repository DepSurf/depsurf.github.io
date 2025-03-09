# Struct: <code>voltagedomain</code>

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
struct voltagedomain {
    char * name;
    bool scalable;
    struct list_head node;
    struct omap_vc_channel * vc;
    const struct omap_vfsm_instance * vfsm;
    struct omap_vp_instance * vp;
    struct omap_voltdm_pmic * pmic;
    struct omap_vp_param * vp_param;
    struct omap_vc_param * vc_param;
    u32 (*)(u8) read;
    void (*)(u32, u8) write;
    u32 (*)(u32, u32, u8) rmw;
    union (anon) sys_clk;
    int (*)(struct voltagedomain *, long unsigned int) scale;
    u32 nominal_volt;
    struct omap_volt_data * volt_data;
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
struct voltagedomain {
    char * name;
    bool scalable;
    struct list_head node;
    struct omap_vc_channel * vc;
    const struct omap_vfsm_instance * vfsm;
    struct omap_vp_instance * vp;
    struct omap_voltdm_pmic * pmic;
    struct omap_vp_param * vp_param;
    struct omap_vc_param * vc_param;
    u32 (*)(u8) read;
    void (*)(u32, u8) write;
    u32 (*)(u32, u32, u8) rmw;
    union (anon) sys_clk;
    int (*)(struct voltagedomain *, long unsigned int) scale;
    u32 nominal_volt;
    struct omap_volt_data * volt_data;
}
```
</details>
</li>
</ul>
