# Struct: <code>scsi_cd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct mutex lock;
    struct gendisk * disk;
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
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
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
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_cd {
    struct scsi_driver * driver;
    unsigned int capacity;
    struct scsi_device * device;
    unsigned int vendor;
    long unsigned int ms_offset;
    unsigned int writeable;
    unsigned int use;
    unsigned int xa_flag;
    unsigned int readcd_known;
    unsigned int readcd_cdda;
    unsigned int media_present;
    int tur_mismatch;
    bool tur_changed;
    bool get_event_changed;
    bool ignore_get_event;
    struct cdrom_device_info cdi;
    struct kref kref;
    struct gendisk * disk;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex lock</code>
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
<b>Field removed. </b>
<code>struct scsi_driver * driver</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kref kref</code>
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
