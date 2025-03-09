# Struct: <code>scsi_device_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    int (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    int (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    int (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    int (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    int (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    int (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
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
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
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
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct scsi_device_handler {
    struct list_head list;
    struct module * module;
    const char * name;
    int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense;
    int (*)(struct scsi_device *) attach;
    void (*)(struct scsi_device *) detach;
    int (*)(struct scsi_device *, activate_complete, void *) activate;
    blk_status_t (*)(struct scsi_device *, struct request *) prep_fn;
    int (*)(struct scsi_device *, const char *) set_params;
    void (*)(struct scsi_device *) rescan;
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
<code>void (*)(struct scsi_device *) rescan</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct scsi_device *, struct request *) prep_fn</code> ➡️ <code>blk_status_t (*)(struct scsi_device *, struct request *) prep_fn</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense</code> ➡️ <code>enum scsi_disposition (*)(struct scsi_device *, struct scsi_sense_hdr *) check_sense</code>
</li>
</ul>
</details>
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
