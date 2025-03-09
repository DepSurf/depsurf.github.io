# Struct: <code>led_classdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_sync;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    unsigned int brightness;
    unsigned int max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    unsigned int brightness;
    unsigned int max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    unsigned int brightness;
    unsigned int max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    unsigned int brightness;
    unsigned int max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    unsigned int brightness;
    unsigned int max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    long unsigned int delayed_delay_on;
    long unsigned int delayed_delay_off;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    const char * hw_control_trigger;
    int (*)(struct led_classdev *, long unsigned int) hw_control_is_supported;
    int (*)(struct led_classdev *, long unsigned int) hw_control_set;
    int (*)(struct led_classdev *, long unsigned int *) hw_control_get;
    struct device * (*)(struct led_classdev *) hw_control_get_device;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    unsigned int brightness;
    unsigned int max_brightness;
    unsigned int color;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    long unsigned int delayed_delay_on;
    long unsigned int delayed_delay_off;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    struct led_hw_trigger_type * trigger_type;
    const char * hw_control_trigger;
    int (*)(struct led_classdev *, long unsigned int) hw_control_is_supported;
    int (*)(struct led_classdev *, long unsigned int) hw_control_set;
    int (*)(struct led_classdev *, long unsigned int *) hw_control_get;
    struct device * (*)(struct led_classdev *) hw_control_get_device;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
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
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
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
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct led_classdev {
    const char * name;
    enum led_brightness brightness;
    enum led_brightness max_brightness;
    int flags;
    long unsigned int work_flags;
    void (*)(struct led_classdev *, enum led_brightness) brightness_set;
    int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking;
    enum led_brightness (*)(struct led_classdev *) brightness_get;
    int (*)(struct led_classdev *, long unsigned int *, long unsigned int *) blink_set;
    int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set;
    int (*)(struct led_classdev *) pattern_clear;
    struct device * dev;
    const struct attribute_group * * groups;
    struct list_head node;
    const char * default_trigger;
    long unsigned int blink_delay_on;
    long unsigned int blink_delay_off;
    struct timer_list blink_timer;
    int blink_brightness;
    int new_blink_brightness;
    void (*)(struct led_classdev *) flash_resume;
    struct work_struct set_brightness_work;
    int delayed_set_value;
    struct rw_semaphore trigger_lock;
    struct led_trigger * trigger;
    struct list_head trig_list;
    void * trigger_data;
    bool activated;
    int brightness_hw_changed;
    struct kernfs_node * brightness_hw_changed_kn;
    struct mutex led_access;
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
<code>int (*)(struct led_classdev *, enum led_brightness) brightness_set_blocking</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct led_classdev *, enum led_brightness) brightness_set_sync</code>
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
<code>long unsigned int work_flags</code>
</li>
<li>
<b>Field added. </b>
<code>int new_blink_brightness</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int brightness_hw_changed</code>
</li>
<li>
<b>Field added. </b>
<code>struct kernfs_node * brightness_hw_changed_kn</code>
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
<code>int (*)(struct led_classdev *, struct led_pattern *, u32, int) pattern_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct led_classdev *) pattern_clear</code>
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
<b>Field added. </b>
<code>struct led_hw_trigger_type * trigger_type</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>enum led_brightness brightness</code> ➡️ <code>unsigned int brightness</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum led_brightness max_brightness</code> ➡️ <code>unsigned int max_brightness</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int delayed_delay_on</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int delayed_delay_off</code>
</li>
<li>
<b>Field added. </b>
<code>const char * hw_control_trigger</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct led_classdev *, long unsigned int) hw_control_is_supported</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct led_classdev *, long unsigned int) hw_control_set</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct led_classdev *, long unsigned int *) hw_control_get</code>
</li>
<li>
<b>Field added. </b>
<code>struct device * (*)(struct led_classdev *) hw_control_get_device</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int color</code>
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
