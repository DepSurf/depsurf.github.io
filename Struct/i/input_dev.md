# Struct: <code>input_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    unsigned int flags;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    unsigned int flags;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    unsigned int flags;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    unsigned int flags;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    unsigned int flags;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
    bool inhibited;
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
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[24] keybit;
    long unsigned int[1] relbit;
    long unsigned int[2] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[4] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[24] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
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
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct input_dev {
    const char * name;
    const char * phys;
    const char * uniq;
    struct input_id id;
    long unsigned int[1] propbit;
    long unsigned int[1] evbit;
    long unsigned int[12] keybit;
    long unsigned int[1] relbit;
    long unsigned int[1] absbit;
    long unsigned int[1] mscbit;
    long unsigned int[1] ledbit;
    long unsigned int[1] sndbit;
    long unsigned int[2] ffbit;
    long unsigned int[1] swbit;
    unsigned int hint_events_per_packet;
    unsigned int keycodemax;
    unsigned int keycodesize;
    void * keycode;
    int (*)(struct input_dev *, const struct input_keymap_entry *, unsigned int *) setkeycode;
    int (*)(struct input_dev *, struct input_keymap_entry *) getkeycode;
    struct ff_device * ff;
    struct input_dev_poller * poller;
    unsigned int repeat_key;
    struct timer_list timer;
    int[2] rep;
    struct input_mt * mt;
    struct input_absinfo * absinfo;
    long unsigned int[12] key;
    long unsigned int[1] led;
    long unsigned int[1] snd;
    long unsigned int[1] sw;
    int (*)(struct input_dev *) open;
    void (*)(struct input_dev *) close;
    int (*)(struct input_dev *, struct file *) flush;
    int (*)(struct input_dev *, unsigned int, unsigned int, int) event;
    struct input_handle * grab;
    spinlock_t event_lock;
    struct mutex mutex;
    unsigned int users;
    bool going_away;
    struct device dev;
    struct list_head h_list;
    struct list_head node;
    unsigned int num_vals;
    unsigned int max_vals;
    struct input_value * vals;
    bool devres_managed;
    ktime_t[3] timestamp;
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
<code>unsigned int flags</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct input_dev_poller * poller</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t[3] timestamp</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<code>bool inhibited</code>
</li>
</ul>
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int[12] keybit</code> ➡️ <code>long unsigned int[24] keybit</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[1] absbit</code> ➡️ <code>long unsigned int[2] absbit</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] ffbit</code> ➡️ <code>long unsigned int[4] ffbit</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[12] key</code> ➡️ <code>long unsigned int[24] key</code>
</li>
</ul>
</details>
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
