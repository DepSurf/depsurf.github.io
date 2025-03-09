# Struct: <code>block_device_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    long int (*)(struct block_device *, sector_t, void * *, long unsigned int *) direct_access;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, bool) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    long int (*)(struct block_device *, sector_t, void * *, pfn_t *, long int) direct_access;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, bool) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    long int (*)(struct block_device *, sector_t, void * *, pfn_t *, long int) direct_access;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, bool) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, bool) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, bool) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *, gfp_t) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    blk_qc_t (*)(struct bio *) submit_bio;
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    blk_qc_t (*)(struct bio *) submit_bio;
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    blk_qc_t (*)(struct bio *) submit_bio;
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    struct module * owner;
    const struct pr_ops * pr_ops;
    int (*)(struct gendisk *, sector_t *) alternative_gpt_sector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    void (*)(struct bio *) submit_bio;
    int (*)(struct bio *, struct io_comp_batch *, unsigned int) poll_bio;
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct gendisk *) free_disk;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    int (*)(struct gendisk *, u8 *, enum blk_unique_id) get_unique_id;
    struct module * owner;
    const struct pr_ops * pr_ops;
    int (*)(struct gendisk *, sector_t *) alternative_gpt_sector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    void (*)(struct bio *) submit_bio;
    int (*)(struct bio *, struct io_comp_batch *, unsigned int) poll_bio;
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, enum req_op) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct gendisk *) free_disk;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    int (*)(struct gendisk *, u8 *, enum blk_unique_id) get_unique_id;
    struct module * owner;
    const struct pr_ops * pr_ops;
    int (*)(struct gendisk *, sector_t *) alternative_gpt_sector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    void (*)(struct bio *) submit_bio;
    int (*)(struct bio *, struct io_comp_batch *, unsigned int) poll_bio;
    int (*)(struct gendisk *, blk_mode_t) open;
    void (*)(struct gendisk *) release;
    int (*)(struct block_device *, blk_mode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, blk_mode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct gendisk *) free_disk;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    int (*)(struct gendisk *, u8 *, enum blk_unique_id) get_unique_id;
    struct module * owner;
    const struct pr_ops * pr_ops;
    int (*)(struct gendisk *, sector_t *) alternative_gpt_sector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    void (*)(struct bio *) submit_bio;
    int (*)(struct bio *, struct io_comp_batch *, unsigned int) poll_bio;
    int (*)(struct gendisk *, blk_mode_t) open;
    void (*)(struct gendisk *) release;
    int (*)(struct block_device *, blk_mode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, blk_mode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    int (*)(struct block_device *, bool) set_read_only;
    void (*)(struct gendisk *) free_disk;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones;
    char * (*)(struct gendisk *, umode_t *) devnode;
    int (*)(struct gendisk *, u8 *, enum blk_unique_id) get_unique_id;
    struct module * owner;
    const struct pr_ops * pr_ops;
    int (*)(struct gendisk *, sector_t *) alternative_gpt_sector;
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
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
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
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct block_device_operations {
    int (*)(struct block_device *, fmode_t) open;
    void (*)(struct gendisk *, fmode_t) release;
    int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl;
    int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl;
    unsigned int (*)(struct gendisk *, unsigned int) check_events;
    int (*)(struct gendisk *) media_changed;
    void (*)(struct gendisk *) unlock_native_capacity;
    int (*)(struct gendisk *) revalidate_disk;
    int (*)(struct block_device *, struct hd_geometry *) getgeo;
    void (*)(struct block_device *, long unsigned int) swap_slot_free_notify;
    int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones;
    struct module * owner;
    const struct pr_ops * pr_ops;
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
<b>Field type changed. </b>
<code>int (*)(struct block_device *, sector_t, struct page *, int) rw_page</code> ➡️ <code>int (*)(struct block_device *, sector_t, struct page *, bool) rw_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int (*)(struct block_device *, sector_t, void * *, long unsigned int *) direct_access</code> ➡️ <code>long int (*)(struct block_device *, sector_t, void * *, pfn_t *, long int) direct_access</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>long int (*)(struct block_device *, sector_t, void * *, pfn_t *, long int) direct_access</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *, gfp_t) report_zones</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct block_device *, sector_t, struct page *, bool) rw_page</code> ➡️ <code>int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *, gfp_t) report_zones</code> ➡️ <code>int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones</code>
</li>
</ul>
</details>
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
<code>char * (*)(struct gendisk *, umode_t *) devnode</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct gendisk *, sector_t, struct blk_zone *, unsigned int *) report_zones</code> ➡️ <code>int (*)(struct gendisk *, sector_t, unsigned int, report_zones_cb, void *) report_zones</code>
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
<code>blk_qc_t (*)(struct bio *) submit_bio</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct block_device *, bool) set_read_only</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct gendisk *) media_changed</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct gendisk *) revalidate_disk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct gendisk *, sector_t *) alternative_gpt_sector</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct bio *, struct io_comp_batch *, unsigned int) poll_bio</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct gendisk *) free_disk</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct gendisk *, u8 *, enum blk_unique_id) get_unique_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>blk_qc_t (*)(struct bio *) submit_bio</code> ➡️ <code>void (*)(struct bio *) submit_bio</code>
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
<code>int (*)(struct block_device *, sector_t, struct page *, unsigned int) rw_page</code> ➡️ <code>int (*)(struct block_device *, sector_t, struct page *, enum req_op) rw_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct block_device *, sector_t, struct page *, enum req_op) rw_page</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct block_device *, fmode_t) open</code> ➡️ <code>int (*)(struct gendisk *, blk_mode_t) open</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct gendisk *, fmode_t) release</code> ➡️ <code>void (*)(struct gendisk *) release</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) ioctl</code> ➡️ <code>int (*)(struct block_device *, blk_mode_t, unsigned int, long unsigned int) ioctl</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct block_device *, fmode_t, unsigned int, long unsigned int) compat_ioctl</code> ➡️ <code>int (*)(struct block_device *, blk_mode_t, unsigned int, long unsigned int) compat_ioctl</code>
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
