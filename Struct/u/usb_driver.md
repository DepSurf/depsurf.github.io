# Struct: <code>usb_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct device_driver driver;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
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
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
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
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_driver {
    const char * name;
    int (*)(struct usb_interface *, const struct usb_device_id *) probe;
    void (*)(struct usb_interface *) disconnect;
    int (*)(struct usb_interface *, unsigned int, void *) unlocked_ioctl;
    int (*)(struct usb_interface *, pm_message_t) suspend;
    int (*)(struct usb_interface *) resume;
    int (*)(struct usb_interface *) reset_resume;
    int (*)(struct usb_interface *) pre_reset;
    int (*)(struct usb_interface *) post_reset;
    const struct usb_device_id * id_table;
    const struct attribute_group * * dev_groups;
    struct usb_dynids dynids;
    struct usbdrv_wrap drvwrap;
    unsigned int no_dynamic_id;
    unsigned int supports_autosuspend;
    unsigned int disable_hub_initiated_lpm;
    unsigned int soft_unbind;
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * dev_groups</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct device_driver driver</code>
</li>
<li>
<b>Field removed. </b>
<code>struct usbdrv_wrap drvwrap</code>
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
