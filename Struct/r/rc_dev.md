# Struct: <code>rc_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
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
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct rc_dev {
    struct device dev;
    bool managed_alloc;
    const struct attribute_group *[5] sysfs_groups;
    const char * device_name;
    const char * input_phys;
    struct input_id input_id;
    const char * driver_name;
    const char * map_name;
    struct rc_map rc_map;
    struct mutex lock;
    unsigned int minor;
    struct ir_raw_event_ctrl * raw;
    struct input_dev * input_dev;
    enum rc_driver_type driver_type;
    bool idle;
    bool encode_wakeup;
    u64 allowed_protocols;
    u64 enabled_protocols;
    u64 allowed_wakeup_protocols;
    enum rc_proto wakeup_protocol;
    struct rc_scancode_filter scancode_filter;
    struct rc_scancode_filter scancode_wakeup_filter;
    u32 scancode_mask;
    u32 users;
    void * priv;
    spinlock_t keylock;
    bool keypressed;
    long unsigned int keyup_jiffies;
    struct timer_list timer_keyup;
    struct timer_list timer_repeat;
    u32 last_keycode;
    enum rc_proto last_protocol;
    u32 last_scancode;
    u8 last_toggle;
    u32 timeout;
    u32 min_timeout;
    u32 max_timeout;
    u32 rx_resolution;
    u32 tx_resolution;
    struct device lirc_dev;
    struct cdev lirc_cdev;
    ktime_t gap_start;
    u64 gap_duration;
    bool gap;
    spinlock_t lirc_fh_lock;
    struct list_head lirc_fh;
    bool registered;
    int (*)(struct rc_dev *, u64 *) change_protocol;
    int (*)(struct rc_dev *) open;
    void (*)(struct rc_dev *) close;
    int (*)(struct rc_dev *, u32) s_tx_mask;
    int (*)(struct rc_dev *, u32) s_tx_carrier;
    int (*)(struct rc_dev *, u32) s_tx_duty_cycle;
    int (*)(struct rc_dev *, u32, u32) s_rx_carrier_range;
    int (*)(struct rc_dev *, unsigned int *, unsigned int) tx_ir;
    void (*)(struct rc_dev *, bool) s_idle;
    int (*)(struct rc_dev *, int) s_learning_mode;
    int (*)(struct rc_dev *, int) s_carrier_report;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_filter;
    int (*)(struct rc_dev *, struct rc_scancode_filter *) s_wakeup_filter;
    int (*)(struct rc_dev *, unsigned int) s_timeout;
}
```
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct device lirc_dev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cdev lirc_cdev</code>
</li>
<li>
<b>Field removed. </b>
<code>ktime_t gap_start</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 gap_duration</code>
</li>
<li>
<b>Field removed. </b>
<code>bool gap</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t lirc_fh_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head lirc_fh</code>
</li>
</ul>
</details>
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
