# Struct: <code>gpmc_timings</code>

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
struct gpmc_timings {
    u32 sync_clk;
    u32 cs_on;
    u32 cs_rd_off;
    u32 cs_wr_off;
    u32 adv_on;
    u32 adv_rd_off;
    u32 adv_wr_off;
    u32 adv_aad_mux_on;
    u32 adv_aad_mux_rd_off;
    u32 adv_aad_mux_wr_off;
    u32 we_on;
    u32 we_off;
    u32 oe_on;
    u32 oe_off;
    u32 oe_aad_mux_on;
    u32 oe_aad_mux_off;
    u32 page_burst_access;
    u32 access;
    u32 rd_cycle;
    u32 wr_cycle;
    u32 bus_turnaround;
    u32 cycle2cycle_delay;
    u32 wait_monitoring;
    u32 clk_activation;
    u32 wr_access;
    u32 wr_data_mux_bus;
    struct gpmc_bool_timings bool_timings;
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
struct gpmc_timings {
    u32 sync_clk;
    u32 cs_on;
    u32 cs_rd_off;
    u32 cs_wr_off;
    u32 adv_on;
    u32 adv_rd_off;
    u32 adv_wr_off;
    u32 adv_aad_mux_on;
    u32 adv_aad_mux_rd_off;
    u32 adv_aad_mux_wr_off;
    u32 we_on;
    u32 we_off;
    u32 oe_on;
    u32 oe_off;
    u32 oe_aad_mux_on;
    u32 oe_aad_mux_off;
    u32 page_burst_access;
    u32 access;
    u32 rd_cycle;
    u32 wr_cycle;
    u32 bus_turnaround;
    u32 cycle2cycle_delay;
    u32 wait_monitoring;
    u32 clk_activation;
    u32 wr_access;
    u32 wr_data_mux_bus;
    struct gpmc_bool_timings bool_timings;
}
```
</details>
</li>
</ul>
