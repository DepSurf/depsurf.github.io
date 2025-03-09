# Struct: <code>rfkill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    long unsigned int hard_block_reasons;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    bool need_sync;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
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
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
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
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rfkill {
    spinlock_t lock;
    enum rfkill_type type;
    long unsigned int state;
    u32 idx;
    bool registered;
    bool persistent;
    bool polling_paused;
    bool suspended;
    const struct rfkill_ops * ops;
    void * data;
    struct led_trigger led_trigger;
    const char * ledtrigname;
    struct device dev;
    struct list_head node;
    struct delayed_work poll_work;
    struct work_struct uevent_work;
    struct work_struct sync_work;
    char[0] name;
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
<code>bool polling_paused</code>
</li>
<li>
<b>Field added. </b>
<code>bool suspended</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int hard_block_reasons</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool need_sync</code>
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
