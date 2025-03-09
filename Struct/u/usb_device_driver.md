# Struct: <code>usb_device_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    bool (*)(struct usb_device *) match;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    int (*)(struct usb_device *) choose_configuration;
    const struct attribute_group * * dev_groups;
    struct device_driver driver;
    const struct usb_device_id * id_table;
    unsigned int supports_autosuspend;
    unsigned int generic_subclass;
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
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
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
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct usb_device_driver {
    const char * name;
    int (*)(struct usb_device *) probe;
    void (*)(struct usb_device *) disconnect;
    int (*)(struct usb_device *, pm_message_t) suspend;
    int (*)(struct usb_device *, pm_message_t) resume;
    const struct attribute_group * * dev_groups;
    struct usbdrv_wrap drvwrap;
    unsigned int supports_autosuspend;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct usb_device *) match</code>
</li>
<li>
<b>Field added. </b>
<code>const struct usb_device_id * id_table</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int generic_subclass</code>
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
<code>int (*)(struct usb_device *) choose_configuration</code>
</li>
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
