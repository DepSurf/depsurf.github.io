# Struct: <code>fman_port</code>

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
struct fman_port {
    void * fm;
    struct device * dev;
    struct fman_rev_info rev_info;
    u8 port_id;
    enum fman_port_type port_type;
    u16 port_speed;
    union fman_port_bmi_regs * bmi_regs;
    struct fman_port_qmi_regs * qmi_regs;
    struct fman_port_hwp_regs * hwp_regs;
    struct fman_sp_buffer_offsets buffer_offsets;
    u8 internal_buf_offset;
    struct fman_ext_pools ext_buf_pools;
    u16 max_frame_length;
    struct fman_port_rsrc open_dmas;
    struct fman_port_rsrc tasks;
    struct fman_port_rsrc fifo_bufs;
    struct fman_port_rx_pools_params rx_pools_params;
    struct fman_port_cfg * cfg;
    struct fman_port_dts_params dts_params;
    u8 ext_pools_num;
    u32 max_port_fifo_size;
    u32 max_num_of_ext_pools;
    u32 max_num_of_sub_portals;
    u32 bm_max_num_of_pools;
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
struct fman_port {
    void * fm;
    struct device * dev;
    struct fman_rev_info rev_info;
    u8 port_id;
    enum fman_port_type port_type;
    u16 port_speed;
    union fman_port_bmi_regs * bmi_regs;
    struct fman_port_qmi_regs * qmi_regs;
    struct fman_port_hwp_regs * hwp_regs;
    struct fman_sp_buffer_offsets buffer_offsets;
    u8 internal_buf_offset;
    struct fman_ext_pools ext_buf_pools;
    u16 max_frame_length;
    struct fman_port_rsrc open_dmas;
    struct fman_port_rsrc tasks;
    struct fman_port_rsrc fifo_bufs;
    struct fman_port_rx_pools_params rx_pools_params;
    struct fman_port_cfg * cfg;
    struct fman_port_dts_params dts_params;
    u8 ext_pools_num;
    u32 max_port_fifo_size;
    u32 max_num_of_ext_pools;
    u32 max_num_of_sub_portals;
    u32 bm_max_num_of_pools;
}
```
</details>
</li>
</ul>
