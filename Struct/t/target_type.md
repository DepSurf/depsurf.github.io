# Struct: <code>target_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_map_request_fn map_rq;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_map_request_fn map_rq;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_direct_access_fn direct_access;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_map_request_fn map_rq;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_direct_access_fn direct_access;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_from_iter_fn dax_copy_from_iter;
    dm_dax_flush_fn dax_flush;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_from_iter_fn dax_copy_from_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    dm_dax_recovery_write_fn dax_recovery_write;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    dm_dax_recovery_write_fn dax_recovery_write;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    dm_dax_recovery_write_fn dax_recovery_write;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_zero_page_range_fn dax_zero_page_range;
    dm_dax_recovery_write_fn dax_recovery_write;
    struct list_head list;
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
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
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
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct target_type {
    uint64_t features;
    const char * name;
    struct module * module;
    unsigned int[3] version;
    dm_ctr_fn ctr;
    dm_dtr_fn dtr;
    dm_map_fn map;
    dm_clone_and_map_request_fn clone_and_map_rq;
    dm_release_clone_request_fn release_clone_rq;
    dm_endio_fn end_io;
    dm_request_endio_fn rq_end_io;
    dm_presuspend_fn presuspend;
    dm_presuspend_undo_fn presuspend_undo;
    dm_postsuspend_fn postsuspend;
    dm_preresume_fn preresume;
    dm_resume_fn resume;
    dm_status_fn status;
    dm_message_fn message;
    dm_prepare_ioctl_fn prepare_ioctl;
    dm_report_zones_fn report_zones;
    dm_busy_fn busy;
    dm_iterate_devices_fn iterate_devices;
    dm_io_hints_fn io_hints;
    dm_dax_direct_access_fn direct_access;
    dm_dax_copy_iter_fn dax_copy_from_iter;
    dm_dax_copy_iter_fn dax_copy_to_iter;
    struct list_head list;
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
<code>dm_direct_access_fn direct_access</code>
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
<b>Field added. </b>
<code>dm_dax_copy_from_iter_fn dax_copy_from_iter</code>
</li>
<li>
<b>Field added. </b>
<code>dm_dax_flush_fn dax_flush</code>
</li>
<li>
<b>Field removed. </b>
<code>dm_map_request_fn map_rq</code>
</li>
<li>
<b>Field type changed. </b>
<code>dm_direct_access_fn direct_access</code> ➡️ <code>dm_dax_direct_access_fn direct_access</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>dm_dax_flush_fn dax_flush</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>dm_dax_copy_iter_fn dax_copy_to_iter</code>
</li>
<li>
<b>Field type changed. </b>
<code>dm_dax_copy_from_iter_fn dax_copy_from_iter</code> ➡️ <code>dm_dax_copy_iter_fn dax_copy_from_iter</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>dm_report_zones_fn report_zones</code>
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
<code>dm_dax_zero_page_range_fn dax_zero_page_range</code>
</li>
</ul>
</details>
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
<code>dm_dax_recovery_write_fn dax_recovery_write</code>
</li>
<li>
<b>Field removed. </b>
<code>dm_dax_copy_iter_fn dax_copy_from_iter</code>
</li>
<li>
<b>Field removed. </b>
<code>dm_dax_copy_iter_fn dax_copy_to_iter</code>
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
