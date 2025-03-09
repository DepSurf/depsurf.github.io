# Struct: <code>sdw_slave_prop</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sdw_slave_prop {
    u32 mipi_revision;
    bool wake_capable;
    bool test_mode_capable;
    bool clk_stop_mode1;
    bool simple_clk_stop_capable;
    u32 clk_stop_timeout;
    u32 ch_prep_timeout;
    enum sdw_clk_stop_reset_behave reset_behave;
    bool high_PHY_capable;
    bool paging_support;
    bool bank_delay_support;
    enum sdw_p15_behave p15_behave;
    bool lane_control_support;
    u32 master_count;
    u32 source_ports;
    u32 sink_ports;
    struct sdw_dp0_prop * dp0_prop;
    struct sdw_dpn_prop * src_dpn_prop;
    struct sdw_dpn_prop * sink_dpn_prop;
}
```
</details>
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct sdw_slave_prop {
    u32 mipi_revision;
    bool wake_capable;
    bool test_mode_capable;
    bool clk_stop_mode1;
    bool simple_clk_stop_capable;
    u32 clk_stop_timeout;
    u32 ch_prep_timeout;
    enum sdw_clk_stop_reset_behave reset_behave;
    bool high_PHY_capable;
    bool paging_support;
    bool bank_delay_support;
    enum sdw_p15_behave p15_behave;
    bool lane_control_support;
    u32 master_count;
    u32 source_ports;
    u32 sink_ports;
    struct sdw_dp0_prop * dp0_prop;
    struct sdw_dpn_prop * src_dpn_prop;
    struct sdw_dpn_prop * sink_dpn_prop;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct sdw_slave_prop {
    u32 mipi_revision;
    bool wake_capable;
    bool test_mode_capable;
    bool clk_stop_mode1;
    bool simple_clk_stop_capable;
    u32 clk_stop_timeout;
    u32 ch_prep_timeout;
    enum sdw_clk_stop_reset_behave reset_behave;
    bool high_PHY_capable;
    bool paging_support;
    bool bank_delay_support;
    enum sdw_p15_behave p15_behave;
    bool lane_control_support;
    u32 master_count;
    u32 source_ports;
    u32 sink_ports;
    struct sdw_dp0_prop * dp0_prop;
    struct sdw_dpn_prop * src_dpn_prop;
    struct sdw_dpn_prop * sink_dpn_prop;
}
```
</details>
</li>
</ul>
