# Struct: <code>dev_pm_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool ignore_children;
    bool early_init;
    bool direct_complete;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    struct timer_list suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int run_wake;
    unsigned int runtime_auto;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    long unsigned int last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool early_init;
    bool direct_complete;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    struct timer_list suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int run_wake;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    long unsigned int last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool early_init;
    bool direct_complete;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    struct timer_list suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int run_wake;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    long unsigned int last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool early_init;
    bool direct_complete;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    struct timer_list suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    long unsigned int last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct timer_list suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    long unsigned int last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct timer_list suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    long unsigned int last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    long unsigned int active_jiffies;
    long unsigned int suspended_jiffies;
    long unsigned int accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int needs_force_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int needs_force_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int needs_force_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    enum rpm_status last_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int needs_force_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    enum rpm_status last_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int needs_force_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    enum rpm_status last_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    bool async_in_progress;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    u64 timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int needs_force_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    enum rpm_status last_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
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
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    unsigned int should_wakeup;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
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
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dev_pm_info {
    pm_message_t power_state;
    unsigned int can_wakeup;
    unsigned int async_suspend;
    bool in_dpm_list;
    bool is_prepared;
    bool is_suspended;
    bool is_noirq_suspended;
    bool is_late_suspended;
    bool no_pm;
    bool early_init;
    bool direct_complete;
    u32 driver_flags;
    spinlock_t lock;
    struct list_head entry;
    struct completion completion;
    struct wakeup_source * wakeup;
    bool wakeup_path;
    bool syscore;
    bool no_pm_callbacks;
    unsigned int must_resume;
    unsigned int may_skip_resume;
    struct hrtimer suspend_timer;
    long unsigned int timer_expires;
    struct work_struct work;
    wait_queue_head_t wait_queue;
    struct wake_irq * wakeirq;
    atomic_t usage_count;
    atomic_t child_count;
    unsigned int disable_depth;
    unsigned int idle_notification;
    unsigned int request_pending;
    unsigned int deferred_resume;
    unsigned int runtime_auto;
    bool ignore_children;
    unsigned int no_callbacks;
    unsigned int irq_safe;
    unsigned int use_autosuspend;
    unsigned int timer_autosuspends;
    unsigned int memalloc_noio;
    unsigned int links_count;
    enum rpm_request request;
    enum rpm_status runtime_status;
    int runtime_error;
    int autosuspend_delay;
    u64 last_busy;
    u64 active_time;
    u64 suspended_time;
    u64 accounting_timestamp;
    struct pm_subsys_data * subsys_data;
    void (*)(struct device *, s32) set_latency_tolerance;
    struct dev_pm_qos * qos;
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
<code>bool no_pm_callbacks</code>
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
<code>bool in_dpm_list</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int links_count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int run_wake</code>
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
<code>u32 driver_flags</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int must_resume</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int may_skip_resume</code>
</li>
</ul>
</details>
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
<code>struct timer_list suspend_timer</code> ➡️ <code>struct hrtimer suspend_timer</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int last_busy</code> ➡️ <code>u64 last_busy</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool no_pm</code>
</li>
<li>
<b>Field added. </b>
<code>u64 active_time</code>
</li>
<li>
<b>Field added. </b>
<code>u64 suspended_time</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int active_jiffies</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int suspended_jiffies</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int accounting_timestamp</code> ➡️ <code>u64 accounting_timestamp</code>
</li>
</ul>
</details>
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
<b>Field type changed. </b>
<code>long unsigned int timer_expires</code> ➡️ <code>u64 timer_expires</code>
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
<code>unsigned int needs_force_resume</code>
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
<b>Field added. </b>
<code>enum rpm_status last_status</code>
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
<code>bool async_in_progress</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int should_wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head entry</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion completion</code>
</li>
<li>
<b>Field removed. </b>
<code>struct wakeup_source * wakeup</code>
</li>
<li>
<b>Field removed. </b>
<code>bool wakeup_path</code>
</li>
<li>
<b>Field removed. </b>
<code>bool syscore</code>
</li>
<li>
<b>Field removed. </b>
<code>bool no_pm_callbacks</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int must_resume</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int may_skip_resume</code>
</li>
</ul>
</details>
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
