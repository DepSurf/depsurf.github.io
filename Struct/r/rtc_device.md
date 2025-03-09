# Struct: <code>rtc_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    char[20] name;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    struct rtc_task * irq_task;
    spinlock_t irq_task_lock;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    char[20] name;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    struct rtc_task * irq_task;
    spinlock_t irq_task_lock;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    char[20] name;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    struct rtc_task * irq_task;
    spinlock_t irq_task_lock;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    struct rtc_task * irq_task;
    spinlock_t irq_task_lock;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    bool registered;
    struct nvmem_config * nvmem_config;
    struct nvmem_device * nvmem;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    struct rtc_task * irq_task;
    spinlock_t irq_task_lock;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    struct nvmem_config * nvmem_config;
    struct nvmem_device * nvmem;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    struct rtc_task * irq_task;
    spinlock_t irq_task_lock;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    struct nvmem_device * nvmem;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long unsigned int set_offset_nsec;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long unsigned int set_offset_nsec;
    long unsigned int[1] features;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long unsigned int set_offset_nsec;
    long unsigned int[1] features;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    long unsigned int set_offset_nsec;
    long unsigned int[1] features;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    long unsigned int set_offset_nsec;
    long unsigned int[1] features;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    long unsigned int set_offset_nsec;
    long unsigned int[1] features;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    long unsigned int set_offset_nsec;
    long unsigned int[1] features;
    time64_t range_min;
    timeu64_t range_max;
    timeu64_t alarm_offset_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
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
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
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
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rtc_device {
    struct device dev;
    struct module * owner;
    int id;
    const struct rtc_class_ops * ops;
    struct mutex ops_lock;
    struct cdev char_dev;
    long unsigned int flags;
    long unsigned int irq_data;
    spinlock_t irq_lock;
    wait_queue_head_t irq_queue;
    struct fasync_struct * async_queue;
    int irq_freq;
    int max_user_freq;
    struct timerqueue_head timerqueue;
    struct rtc_timer aie_timer;
    struct rtc_timer uie_rtctimer;
    struct hrtimer pie_timer;
    int pie_enabled;
    struct work_struct irqwork;
    int uie_unsupported;
    long int set_offset_nsec;
    bool registered;
    bool nvram_old_abi;
    struct bin_attribute * nvram;
    time64_t range_min;
    timeu64_t range_max;
    time64_t start_secs;
    time64_t offset_secs;
    bool set_start_time;
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
<b>Field added. </b>
<code>bool registered</code>
</li>
<li>
<b>Field added. </b>
<code>struct nvmem_config * nvmem_config</code>
</li>
<li>
<b>Field added. </b>
<code>struct nvmem_device * nvmem</code>
</li>
<li>
<b>Field added. </b>
<code>bool nvram_old_abi</code>
</li>
<li>
<b>Field added. </b>
<code>struct bin_attribute * nvram</code>
</li>
<li>
<b>Field removed. </b>
<code>char[20] name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long int set_offset_nsec</code>
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
<code>time64_t range_min</code>
</li>
<li>
<b>Field added. </b>
<code>timeu64_t range_max</code>
</li>
<li>
<b>Field added. </b>
<code>time64_t start_secs</code>
</li>
<li>
<b>Field added. </b>
<code>time64_t offset_secs</code>
</li>
<li>
<b>Field added. </b>
<code>bool set_start_time</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nvmem_config * nvmem_config</code>
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
<code>struct rtc_task * irq_task</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t irq_task_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nvmem_device * nvmem</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool registered</code>
</li>
<li>
<b>Field removed. </b>
<code>bool nvram_old_abi</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bin_attribute * nvram</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int set_offset_nsec</code> ➡️ <code>long unsigned int set_offset_nsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int[1] features</code>
</li>
</ul>
</details>
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
<code>int uie_unsupported</code>
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
<code>timeu64_t alarm_offset_max</code>
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
