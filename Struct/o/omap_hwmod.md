# Struct: <code>omap_hwmod</code>

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
struct omap_hwmod {
    const char * name;
    struct omap_hwmod_class * class;
    struct omap_device * od;
    struct omap_hwmod_rst_info * rst_lines;
    union (anon) prcm;
    const char * main_clk;
    struct clk * _clk;
    struct omap_hwmod_opt_clk * opt_clks;
    const char * clkdm_name;
    struct clockdomain * clkdm;
    struct list_head slave_ports;
    void * dev_attr;
    u32 _sysc_cache;
    void * _mpu_rt_va;
    spinlock_t _lock;
    struct lock_class_key hwmod_key;
    struct list_head node;
    struct omap_hwmod_ocp_if * _mpu_port;
    u32 flags;
    u8 mpu_rt_idx;
    u8 response_lat;
    u8 rst_lines_cnt;
    u8 opt_clks_cnt;
    u8 slaves_cnt;
    u8 hwmods_cnt;
    u8 _int_flags;
    u8 _state;
    u8 _postsetup_state;
    struct omap_hwmod * parent_hwmod;
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
struct omap_hwmod {
    const char * name;
    struct omap_hwmod_class * class;
    struct omap_device * od;
    struct omap_hwmod_rst_info * rst_lines;
    union (anon) prcm;
    const char * main_clk;
    struct clk * _clk;
    struct omap_hwmod_opt_clk * opt_clks;
    const char * clkdm_name;
    struct clockdomain * clkdm;
    struct list_head slave_ports;
    void * dev_attr;
    u32 _sysc_cache;
    void * _mpu_rt_va;
    spinlock_t _lock;
    struct lock_class_key hwmod_key;
    struct list_head node;
    struct omap_hwmod_ocp_if * _mpu_port;
    u32 flags;
    u8 mpu_rt_idx;
    u8 response_lat;
    u8 rst_lines_cnt;
    u8 opt_clks_cnt;
    u8 slaves_cnt;
    u8 hwmods_cnt;
    u8 _int_flags;
    u8 _state;
    u8 _postsetup_state;
    struct omap_hwmod * parent_hwmod;
}
```
</details>
</li>
</ul>
