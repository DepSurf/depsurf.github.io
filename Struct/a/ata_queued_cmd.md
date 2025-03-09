# Struct: <code>ata_queued_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
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
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
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
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ata_queued_cmd {
    struct ata_port * ap;
    struct ata_device * dev;
    struct scsi_cmnd * scsicmd;
    void (*)(struct scsi_cmnd *) scsidone;
    struct ata_taskfile tf;
    u8[16] cdb;
    long unsigned int flags;
    unsigned int tag;
    unsigned int hw_tag;
    unsigned int n_elem;
    unsigned int orig_n_elem;
    int dma_dir;
    unsigned int sect_size;
    unsigned int nbytes;
    unsigned int extrabytes;
    unsigned int curbytes;
    struct scatterlist sgent;
    struct scatterlist * sg;
    struct scatterlist * cursg;
    unsigned int cursg_ofs;
    unsigned int err_mask;
    struct ata_taskfile result_tf;
    ata_qc_cb_t complete_fn;
    void * private_data;
    void * lldd_task;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int hw_tag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
