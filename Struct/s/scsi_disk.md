# Struct: <code>scsi_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    unsigned int nr_zones;
    unsigned int zone_blocks;
    unsigned int zone_shift;
    long unsigned int * zones_wlock;
    unsigned int zones_optimal_open;
    unsigned int zones_optimal_nonseq;
    unsigned int zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    unsigned int nr_zones;
    unsigned int zone_blocks;
    unsigned int zone_shift;
    long unsigned int * zones_wlock;
    unsigned int zones_optimal_open;
    unsigned int zones_optimal_nonseq;
    unsigned int zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    unsigned int nr_zones;
    unsigned int zone_blocks;
    unsigned int zone_shift;
    long unsigned int * zones_wlock;
    unsigned int zones_optimal_open;
    unsigned int zones_optimal_nonseq;
    unsigned int zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zone_shift;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 rev_nr_zones;
    u32 zone_blocks;
    u32 rev_zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 rev_nr_zones;
    u32 zone_blocks;
    u32 rev_zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 rev_nr_zones;
    u32 zone_blocks;
    u32 rev_zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_device * device;
    struct device disk_dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    struct zoned_disk_info early_zone_info;
    struct zoned_disk_info zone_info;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 zone_starting_lba_gran;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 min_xfer_blocks;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    u8 nr_actuators;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_device * device;
    struct device disk_dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    struct zoned_disk_info early_zone_info;
    struct zoned_disk_info zone_info;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 zone_starting_lba_gran;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 min_xfer_blocks;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    u8 nr_actuators;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_device * device;
    struct device disk_dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    struct zoned_disk_info early_zone_info;
    struct zoned_disk_info zone_info;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 zone_starting_lba_gran;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 min_xfer_blocks;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    u8 nr_actuators;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_device * device;
    struct device disk_dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    struct zoned_disk_info early_zone_info;
    struct zoned_disk_info zone_info;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    u32 zone_starting_lba_gran;
    u32 * zones_wp_offset;
    spinlock_t zones_wp_offset_lock;
    u32 * rev_wp_offset;
    struct mutex rev_mutex;
    struct work_struct zone_wp_offset_work;
    char * zone_wp_update_buf;
    atomic_t openers;
    sector_t capacity;
    int max_retries;
    u32 min_xfer_blocks;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    u8 nr_actuators;
    bool suspended;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
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
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
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
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_disk {
    struct scsi_driver * driver;
    struct scsi_device * device;
    struct device dev;
    struct gendisk * disk;
    struct opal_dev * opal_dev;
    u32 nr_zones;
    u32 zone_blocks;
    u32 zones_optimal_open;
    u32 zones_optimal_nonseq;
    u32 zones_max_open;
    atomic_t openers;
    sector_t capacity;
    u32 max_xfer_blocks;
    u32 opt_xfer_blocks;
    u32 max_ws_blocks;
    u32 max_unmap_blocks;
    u32 unmap_granularity;
    u32 unmap_alignment;
    u32 index;
    unsigned int physical_block_size;
    unsigned int max_medium_access_timeouts;
    unsigned int medium_access_timed_out;
    u8 media_present;
    u8 write_prot;
    u8 protection_type;
    u8 provisioning_mode;
    u8 zeroing_mode;
    unsigned int ATO;
    unsigned int cache_override;
    unsigned int WCE;
    unsigned int RCD;
    unsigned int DPOFUA;
    unsigned int first_scan;
    unsigned int lbpme;
    unsigned int lbprz;
    unsigned int lbpu;
    unsigned int lbpws;
    unsigned int lbpws10;
    unsigned int lbpvpd;
    unsigned int ws10;
    unsigned int ws16;
    unsigned int rc_basis;
    unsigned int zoned;
    unsigned int urswrz;
    unsigned int security;
    unsigned int ignore_medium_access_errors;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int nr_zones</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zone_blocks</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zone_shift</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * zones_wlock</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zones_optimal_open</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zones_optimal_nonseq</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zones_max_open</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rc_basis</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int zoned</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int urswrz</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct opal_dev * opal_dev</code>
</li>
<li>
<b>Field added. </b>
<code>u8 zeroing_mode</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int security</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ignore_medium_access_errors</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long unsigned int * zones_wlock</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int nr_zones</code> ➡️ <code>u32 nr_zones</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int zone_blocks</code> ➡️ <code>u32 zone_blocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int zone_shift</code> ➡️ <code>u32 zone_shift</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int zones_optimal_open</code> ➡️ <code>u32 zones_optimal_open</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int zones_optimal_nonseq</code> ➡️ <code>u32 zones_optimal_nonseq</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int zones_max_open</code> ➡️ <code>u32 zones_max_open</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u32 zone_shift</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 * zones_wp_offset</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t zones_wp_offset_lock</code>
</li>
<li>
<b>Field added. </b>
<code>u32 * rev_wp_offset</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex rev_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct zone_wp_offset_work</code>
</li>
<li>
<b>Field added. </b>
<code>char * zone_wp_update_buf</code>
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
<code>u32 rev_nr_zones</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rev_zone_blocks</code>
</li>
<li>
<b>Field added. </b>
<code>int max_retries</code>
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
<code>struct device disk_dev</code>
</li>
<li>
<b>Field added. </b>
<code>struct zoned_disk_info early_zone_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct zoned_disk_info zone_info</code>
</li>
<li>
<b>Field added. </b>
<code>u32 zone_starting_lba_gran</code>
</li>
<li>
<b>Field added. </b>
<code>u32 min_xfer_blocks</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nr_actuators</code>
</li>
<li>
<b>Field removed. </b>
<code>struct scsi_driver * driver</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device dev</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 nr_zones</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rev_nr_zones</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 zone_blocks</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rev_zone_blocks</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool suspended</code>
</li>
</ul>
</details>
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
