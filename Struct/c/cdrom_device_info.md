# Struct: <code>cdrom_device_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
    __s64 last_media_change_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
    __s64 last_media_change_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
    bool opened_for_data;
    __s64 last_media_change_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
    bool opened_for_data;
    __s64 last_media_change_ms;
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
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
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
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cdrom_device_info {
    const struct cdrom_device_ops * ops;
    struct list_head list;
    struct gendisk * disk;
    void * handle;
    int mask;
    int speed;
    int capacity;
    unsigned int options;
    unsigned int mc_flags;
    unsigned int vfs_events;
    unsigned int ioctl_events;
    int use_count;
    char[20] name;
    __u8 sanyo_slot;
    __u8 keeplocked;
    __u8 reserved;
    int cdda_method;
    __u8 last_sense;
    __u8 media_written;
    short unsigned int mmc3_profile;
    int for_data;
    int (*)(struct cdrom_device_info *) exit;
    int mrw_mode_page;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct cdrom_device_ops * ops</code> ➡️ <code>const struct cdrom_device_ops * ops</code>
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
<code>__s64 last_media_change_ms</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool opened_for_data</code>
</li>
<li>
<b>Field removed. </b>
<code>int for_data</code>
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
