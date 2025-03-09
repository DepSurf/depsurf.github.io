# Struct: <code>watchdog_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct cdev cdev;
    struct device * dev;
    struct device * parent;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    void * driver_data;
    struct mutex lock;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    struct notifier_block pm_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    struct notifier_block pm_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    struct notifier_block pm_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    struct notifier_block pm_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    struct notifier_block pm_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
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
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
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
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct watchdog_device {
    int id;
    struct device * parent;
    const struct attribute_group * * groups;
    const struct watchdog_info * info;
    const struct watchdog_ops * ops;
    const struct watchdog_governor * gov;
    unsigned int bootstatus;
    unsigned int timeout;
    unsigned int pretimeout;
    unsigned int min_timeout;
    unsigned int max_timeout;
    unsigned int min_hw_heartbeat_ms;
    unsigned int max_hw_heartbeat_ms;
    struct notifier_block reboot_nb;
    struct notifier_block restart_nb;
    void * driver_data;
    struct watchdog_core_data * wd_data;
    long unsigned int status;
    struct list_head deferred;
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
<code>const struct attribute_group * * groups</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int min_hw_heartbeat_ms</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int max_hw_heartbeat_ms</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block reboot_nb</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block restart_nb</code>
</li>
<li>
<b>Field added. </b>
<code>struct watchdog_core_data * wd_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cdev cdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct watchdog_governor * gov</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pretimeout</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct notifier_block pm_nb</code>
</li>
</ul>
</details>
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
