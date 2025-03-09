# Struct: <code>fman_state_struct</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct fman_state_struct {
    u8 fm_id;
    u16 fm_clk_freq;
    struct fman_rev_info rev_info;
    bool enabled_time_stamp;
    u8 count1_micro_bit;
    u8 total_num_of_tasks;
    u8 accumulated_num_of_tasks;
    u32 accumulated_fifo_size;
    u8 accumulated_num_of_open_dmas;
    u8 accumulated_num_of_deq_tnums;
    u32 exceptions;
    u32 extra_fifo_pool_size;
    u8 extra_tasks_pool_size;
    u8 extra_open_dmas_pool_size;
    u16[10] port_mfl;
    u16[10] mac_mfl;
    u32 fm_iram_size;
    u32 dma_thresh_max_commq;
    u32 dma_thresh_max_buf;
    u32 max_num_of_open_dmas;
    u32 qmi_max_num_of_tnums;
    u32 qmi_def_tnums_thresh;
    u32 bmi_max_num_of_tasks;
    u32 bmi_max_fifo_size;
    u32 fm_port_num_of_cg;
    u32 num_of_rx_ports;
    u32 total_fifo_size;
    u32 qman_channel_base;
    u32 num_of_qman_channels;
    struct resource * res;
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct fman_state_struct {
    u8 fm_id;
    u16 fm_clk_freq;
    struct fman_rev_info rev_info;
    bool enabled_time_stamp;
    u8 count1_micro_bit;
    u8 total_num_of_tasks;
    u8 accumulated_num_of_tasks;
    u32 accumulated_fifo_size;
    u8 accumulated_num_of_open_dmas;
    u8 accumulated_num_of_deq_tnums;
    u32 exceptions;
    u32 extra_fifo_pool_size;
    u8 extra_tasks_pool_size;
    u8 extra_open_dmas_pool_size;
    u16[10] port_mfl;
    u16[10] mac_mfl;
    u32 fm_iram_size;
    u32 dma_thresh_max_commq;
    u32 dma_thresh_max_buf;
    u32 max_num_of_open_dmas;
    u32 qmi_max_num_of_tnums;
    u32 qmi_def_tnums_thresh;
    u32 bmi_max_num_of_tasks;
    u32 bmi_max_fifo_size;
    u32 fm_port_num_of_cg;
    u32 num_of_rx_ports;
    u32 total_fifo_size;
    u32 qman_channel_base;
    u32 num_of_qman_channels;
    struct resource * res;
}
```
</details>
</li>
</ul>
