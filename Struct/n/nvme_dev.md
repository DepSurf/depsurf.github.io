# Struct: <code>nvme_dev</code>

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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct nvme_dev {
    struct nvme_queue * queues;
    struct blk_mq_tag_set tagset;
    struct blk_mq_tag_set admin_tagset;
    u32 * dbs;
    struct device * dev;
    struct dma_pool * prp_page_pool;
    struct dma_pool * prp_small_pool;
    unsigned int online_queues;
    unsigned int max_qid;
    unsigned int[3] io_queues;
    unsigned int num_vecs;
    int q_depth;
    int io_sqes;
    u32 db_stride;
    void * bar;
    long unsigned int bar_mapped_size;
    struct work_struct remove_work;
    struct mutex shutdown_lock;
    bool subsystem;
    u64 cmb_size;
    bool cmb_use_sqes;
    u32 cmbsz;
    u32 cmbloc;
    struct nvme_ctrl ctrl;
    u32 last_ps;
    mempool_t * iod_mempool;
    u32 * dbbuf_dbs;
    dma_addr_t dbbuf_dbs_dma_addr;
    u32 * dbbuf_eis;
    dma_addr_t dbbuf_eis_dma_addr;
    u64 host_mem_size;
    u32 nr_host_mem_descs;
    dma_addr_t host_mem_descs_dma;
    struct nvme_host_mem_buf_desc * host_mem_descs;
    void * * host_mem_desc_bufs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nvme_dev {
    struct nvme_queue * queues;
    struct blk_mq_tag_set tagset;
    struct blk_mq_tag_set admin_tagset;
    u32 * dbs;
    struct device * dev;
    struct dma_pool * prp_page_pool;
    struct dma_pool * prp_small_pool;
    unsigned int online_queues;
    unsigned int max_qid;
    unsigned int[3] io_queues;
    unsigned int num_vecs;
    int q_depth;
    int io_sqes;
    u32 db_stride;
    void * bar;
    long unsigned int bar_mapped_size;
    struct work_struct remove_work;
    struct mutex shutdown_lock;
    bool subsystem;
    u64 cmb_size;
    bool cmb_use_sqes;
    u32 cmbsz;
    u32 cmbloc;
    struct nvme_ctrl ctrl;
    u32 last_ps;
    mempool_t * iod_mempool;
    u32 * dbbuf_dbs;
    dma_addr_t dbbuf_dbs_dma_addr;
    u32 * dbbuf_eis;
    dma_addr_t dbbuf_eis_dma_addr;
    u64 host_mem_size;
    u32 nr_host_mem_descs;
    dma_addr_t host_mem_descs_dma;
    struct nvme_host_mem_buf_desc * host_mem_descs;
    void * * host_mem_desc_bufs;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
struct nvme_dev {
    struct nvme_queue * queues;
    struct blk_mq_tag_set tagset;
    struct blk_mq_tag_set admin_tagset;
    u32 * dbs;
    struct device * dev;
    struct dma_pool * prp_page_pool;
    struct dma_pool * prp_small_pool;
    unsigned int online_queues;
    unsigned int max_qid;
    unsigned int[3] io_queues;
    unsigned int num_vecs;
    int q_depth;
    int io_sqes;
    u32 db_stride;
    void * bar;
    long unsigned int bar_mapped_size;
    struct work_struct remove_work;
    struct mutex shutdown_lock;
    bool subsystem;
    u64 cmb_size;
    bool cmb_use_sqes;
    u32 cmbsz;
    u32 cmbloc;
    struct nvme_ctrl ctrl;
    u32 last_ps;
    mempool_t * iod_mempool;
    u32 * dbbuf_dbs;
    dma_addr_t dbbuf_dbs_dma_addr;
    u32 * dbbuf_eis;
    dma_addr_t dbbuf_eis_dma_addr;
    u64 host_mem_size;
    u32 nr_host_mem_descs;
    dma_addr_t host_mem_descs_dma;
    struct nvme_host_mem_buf_desc * host_mem_descs;
    void * * host_mem_desc_bufs;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct nvme_dev {
    struct nvme_queue * queues;
    struct blk_mq_tag_set tagset;
    struct blk_mq_tag_set admin_tagset;
    u32 * dbs;
    struct device * dev;
    struct dma_pool * prp_page_pool;
    struct dma_pool * prp_small_pool;
    unsigned int online_queues;
    unsigned int max_qid;
    unsigned int[3] io_queues;
    unsigned int num_vecs;
    int q_depth;
    int io_sqes;
    u32 db_stride;
    void * bar;
    long unsigned int bar_mapped_size;
    struct work_struct remove_work;
    struct mutex shutdown_lock;
    bool subsystem;
    u64 cmb_size;
    bool cmb_use_sqes;
    u32 cmbsz;
    u32 cmbloc;
    struct nvme_ctrl ctrl;
    u32 last_ps;
    mempool_t * iod_mempool;
    u32 * dbbuf_dbs;
    dma_addr_t dbbuf_dbs_dma_addr;
    u32 * dbbuf_eis;
    dma_addr_t dbbuf_eis_dma_addr;
    u64 host_mem_size;
    u32 nr_host_mem_descs;
    dma_addr_t host_mem_descs_dma;
    struct nvme_host_mem_buf_desc * host_mem_descs;
    void * * host_mem_desc_bufs;
}
```
</details>
</li>
</ul>
