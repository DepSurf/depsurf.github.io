# Struct: <code>ata_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[16] ncq_send_recv_cmds;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    struct ata_cpr_log * cpr_log;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    unsigned int pio_mask;
    unsigned int mwdma_mask;
    unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    struct ata_cpr_log * cpr_log;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    unsigned int pio_mask;
    unsigned int mwdma_mask;
    unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    struct ata_cpr_log * cpr_log;
    u8[512] cdl;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    unsigned int pio_mask;
    unsigned int mwdma_mask;
    unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    struct ata_cpr_log * cpr_log;
    u8[512] cdl;
    int spdn_cnt;
    struct ata_ering ering;
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
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
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
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ata_device {
    struct ata_link * link;
    unsigned int devno;
    unsigned int horkage;
    long unsigned int flags;
    struct scsi_device * sdev;
    void * private_data;
    union acpi_object * gtf_cache;
    unsigned int gtf_filter;
    void * zpodd;
    struct device tdev;
    u64 n_sectors;
    u64 n_native_sectors;
    unsigned int class;
    long unsigned int unpark_deadline;
    u8 pio_mode;
    u8 dma_mode;
    u8 xfer_mode;
    unsigned int xfer_shift;
    unsigned int multi_count;
    unsigned int max_sectors;
    unsigned int cdb_len;
    long unsigned int pio_mask;
    long unsigned int mwdma_mask;
    long unsigned int udma_mask;
    u16 cylinders;
    u16 heads;
    u16 sectors;
    u16[256] id;
    u32[128] gscr;
    u8[8] devslp_timing;
    u8[20] ncq_send_recv_cmds;
    u8[64] ncq_non_data_cmds;
    u32 zac_zoned_cap;
    u32 zac_zones_optimal_open;
    u32 zac_zones_optimal_nonseq;
    u32 zac_zones_max_open;
    int spdn_cnt;
    struct ata_ering ering;
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
<code>u8[64] ncq_non_data_cmds</code>
</li>
<li>
<b>Field added. </b>
<code>u32 zac_zoned_cap</code>
</li>
<li>
<b>Field added. </b>
<code>u32 zac_zones_optimal_open</code>
</li>
<li>
<b>Field added. </b>
<code>u32 zac_zones_optimal_nonseq</code>
</li>
<li>
<b>Field added. </b>
<code>u32 zac_zones_max_open</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[16] ncq_send_recv_cmds</code> ➡️ <code>u8[20] ncq_send_recv_cmds</code>
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ata_cpr_log * cpr_log</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int pio_mask</code> ➡️ <code>unsigned int pio_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int mwdma_mask</code> ➡️ <code>unsigned int mwdma_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int udma_mask</code> ➡️ <code>unsigned int udma_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8[512] cdl</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>union acpi_object * gtf_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int gtf_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>void * zpodd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>union acpi_object * gtf_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int gtf_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>void * zpodd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>union acpi_object * gtf_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int gtf_filter</code>
</li>
<li>
<b>Field removed. </b>
<code>void * zpodd</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void * zpodd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void * zpodd</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
