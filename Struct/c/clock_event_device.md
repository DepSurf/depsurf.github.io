# Struct: <code>clock_event_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
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
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
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
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct clock_event_device {
    void (*)(struct clock_event_device *) event_handler;
    int (*)(long unsigned int, struct clock_event_device *) set_next_event;
    int (*)(ktime_t, struct clock_event_device *) set_next_ktime;
    ktime_t next_event;
    u64 max_delta_ns;
    u64 min_delta_ns;
    u32 mult;
    u32 shift;
    enum clock_event_state state_use_accessors;
    unsigned int features;
    long unsigned int retries;
    int (*)(struct clock_event_device *) set_state_periodic;
    int (*)(struct clock_event_device *) set_state_oneshot;
    int (*)(struct clock_event_device *) set_state_oneshot_stopped;
    int (*)(struct clock_event_device *) set_state_shutdown;
    int (*)(struct clock_event_device *) tick_resume;
    void (*)(const struct cpumask *) broadcast;
    void (*)(struct clock_event_device *) suspend;
    void (*)(struct clock_event_device *) resume;
    long unsigned int min_delta_ticks;
    long unsigned int max_delta_ticks;
    const char * name;
    int rating;
    int irq;
    int bound_on;
    const struct cpumask * cpumask;
    struct list_head list;
    struct module * owner;
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
