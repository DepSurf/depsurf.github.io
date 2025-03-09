# Struct: <code>fman_port_cfg</code>

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
struct fman_port_cfg {
    u32 dflt_fqid;
    u32 err_fqid;
    u32 pcd_base_fqid;
    u32 pcd_fqs_count;
    u8 deq_sp;
    bool deq_high_priority;
    enum fman_port_deq_type deq_type;
    enum fman_port_deq_prefetch deq_prefetch_option;
    u16 deq_byte_cnt;
    u8 cheksum_last_bytes_ignore;
    u8 rx_cut_end_bytes;
    struct fman_buf_pool_depletion buf_pool_depletion;
    struct fman_ext_pools ext_buf_pools;
    u32 tx_fifo_min_level;
    u32 tx_fifo_low_comf_level;
    u32 rx_pri_elevation;
    u32 rx_fifo_thr;
    struct fman_sp_buf_margins buf_margins;
    u32 int_buf_start_margin;
    struct fman_sp_int_context_data_copy int_context;
    u32 discard_mask;
    u32 err_mask;
    struct fman_buffer_prefix_content buffer_prefix_content;
    bool dont_release_buf;
    u8 rx_fd_bits;
    u32 tx_fifo_deq_pipeline_depth;
    bool errata_A006320;
    bool excessive_threshold_register;
    bool fmbm_tfne_has_features;
    enum fman_port_dma_swap dma_swap_data;
    enum fman_port_color color;
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
struct fman_port_cfg {
    u32 dflt_fqid;
    u32 err_fqid;
    u32 pcd_base_fqid;
    u32 pcd_fqs_count;
    u8 deq_sp;
    bool deq_high_priority;
    enum fman_port_deq_type deq_type;
    enum fman_port_deq_prefetch deq_prefetch_option;
    u16 deq_byte_cnt;
    u8 cheksum_last_bytes_ignore;
    u8 rx_cut_end_bytes;
    struct fman_buf_pool_depletion buf_pool_depletion;
    struct fman_ext_pools ext_buf_pools;
    u32 tx_fifo_min_level;
    u32 tx_fifo_low_comf_level;
    u32 rx_pri_elevation;
    u32 rx_fifo_thr;
    struct fman_sp_buf_margins buf_margins;
    u32 int_buf_start_margin;
    struct fman_sp_int_context_data_copy int_context;
    u32 discard_mask;
    u32 err_mask;
    struct fman_buffer_prefix_content buffer_prefix_content;
    bool dont_release_buf;
    u8 rx_fd_bits;
    u32 tx_fifo_deq_pipeline_depth;
    bool errata_A006320;
    bool excessive_threshold_register;
    bool fmbm_tfne_has_features;
    enum fman_port_dma_swap dma_swap_data;
    enum fman_port_color color;
}
```
</details>
</li>
</ul>
