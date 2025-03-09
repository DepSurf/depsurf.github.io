# Struct: <code>dma_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    struct mutex chan_mutex;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    struct mutex chan_mutex;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    struct mutex chan_mutex;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    struct mutex chan_mutex;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_memcpy_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dma_device {
    struct kref ref;
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    enum dma_desc_metadata_mode desc_metadata_modes;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    struct ida chan_ida;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 min_burst;
    u32 max_burst;
    u32 max_sg_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    int (*)(struct dma_chan *) device_router_config;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
    void (*)(struct dma_device *) device_release;
    void (*)(struct seq_file *, struct dma_device *) dbg_summary_show;
    struct dentry * dbg_dev_root;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dma_device {
    unsigned int chancnt;
    unsigned int privatecnt;
    struct list_head channels;
    struct list_head global_node;
    struct dma_filter filter;
    dma_cap_mask_t cap_mask;
    short unsigned int max_xor;
    short unsigned int max_pq;
    enum dmaengine_alignment copy_align;
    enum dmaengine_alignment xor_align;
    enum dmaengine_alignment pq_align;
    enum dmaengine_alignment fill_align;
    int dev_id;
    struct device * dev;
    struct module * owner;
    u32 src_addr_widths;
    u32 dst_addr_widths;
    u32 directions;
    u32 max_burst;
    bool descriptor_reuse;
    enum dma_residue_granularity residue_granularity;
    int (*)(struct dma_chan *) device_alloc_chan_resources;
    void (*)(struct dma_chan *) device_free_chan_resources;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t, size_t, long unsigned int) device_prep_dma_memcpy;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, dma_addr_t *, unsigned int, size_t, long unsigned int) device_prep_dma_xor;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, unsigned int, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_xor_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, long unsigned int) device_prep_dma_pq;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t *, dma_addr_t *, unsigned int, const unsigned char *, size_t, enum sum_check_flags *, long unsigned int) device_prep_dma_pq_val;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, int, size_t, long unsigned int) device_prep_dma_memset;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, int, long unsigned int) device_prep_dma_memset_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, long unsigned int) device_prep_dma_interrupt;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, enum dma_transfer_direction, long unsigned int, void *) device_prep_slave_sg;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, size_t, size_t, enum dma_transfer_direction, long unsigned int) device_prep_dma_cyclic;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct dma_interleaved_template *, long unsigned int) device_prep_interleaved_dma;
    struct dma_async_tx_descriptor * (*)(struct dma_chan *, dma_addr_t, u64, long unsigned int) device_prep_dma_imm_data;
    int (*)(struct dma_chan *, struct dma_slave_config *) device_config;
    int (*)(struct dma_chan *) device_pause;
    int (*)(struct dma_chan *) device_resume;
    int (*)(struct dma_chan *) device_terminate_all;
    void (*)(struct dma_chan *) device_synchronize;
    enum dma_status (*)(struct dma_chan *, dma_cookie_t, struct dma_tx_state *) device_tx_status;
    void (*)(struct dma_chan *) device_issue_pending;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_filter filter</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_burst</code>
</li>
<li>
<b>Field added. </b>
<code>bool descriptor_reuse</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dma_chan *) device_synchronize</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_sg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct module * owner</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kref ref</code>
</li>
<li>
<b>Field added. </b>
<code>enum dma_desc_metadata_mode desc_metadata_modes</code>
</li>
<li>
<b>Field added. </b>
<code>struct ida chan_ida</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex chan_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dma_device *) device_release</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct seq_file *, struct dma_device *) dbg_summary_show</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * dbg_dev_root</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 min_burst</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_sg_burst</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dma_chan *) device_router_config</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dma_chan *, struct dma_slave_caps *) device_caps</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_memcpy_sg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex chan_mutex</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct dma_async_tx_descriptor * (*)(struct dma_chan *, struct scatterlist *, unsigned int, struct scatterlist *, unsigned int, long unsigned int) device_prep_dma_memcpy_sg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
