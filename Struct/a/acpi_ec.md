# Struct: <code>acpi_ec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    long unsigned int gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    long unsigned int gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    long unsigned int gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool saved_busy_polling;
    unsigned int saved_polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    long unsigned int gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    unsigned int events_in_progress;
    unsigned int queries_in_progress;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    enum acpi_ec_event_state event_state;
    unsigned int events_to_process;
    unsigned int events_in_progress;
    unsigned int queries_in_progress;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    acpi_handle address_space_handler_holder;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    enum acpi_ec_event_state event_state;
    unsigned int events_to_process;
    unsigned int events_in_progress;
    unsigned int queries_in_progress;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    acpi_handle address_space_handler_holder;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    enum acpi_ec_event_state event_state;
    unsigned int events_to_process;
    unsigned int events_in_progress;
    unsigned int queries_in_progress;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    acpi_handle address_space_handler_holder;
    int gpe;
    int irq;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    enum acpi_ec_event_state event_state;
    unsigned int events_to_process;
    unsigned int events_in_progress;
    unsigned int queries_in_progress;
    bool busy_polling;
    unsigned int polling_guard;
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
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool saved_busy_polling</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int saved_polling_guard</code>
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
<code>bool busy_polling</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int polling_guard</code>
</li>
<li>
<b>Field removed. </b>
<code>bool saved_busy_polling</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int saved_polling_guard</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>long unsigned int gpe</code> ➡️ <code>u32 gpe</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int irq</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 gpe</code> ➡️ <code>int gpe</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int events_in_progress</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int queries_in_progress</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum acpi_ec_event_state event_state</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int events_to_process</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int nr_pending_queries</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>acpi_handle address_space_handler_holder</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_ec {
    acpi_handle handle;
    u32 gpe;
    long unsigned int command_addr;
    long unsigned int data_addr;
    bool global_lock;
    long unsigned int flags;
    long unsigned int reference_count;
    struct mutex mutex;
    wait_queue_head_t wait;
    struct list_head list;
    struct transaction * curr;
    spinlock_t lock;
    struct work_struct work;
    long unsigned int timestamp;
    long unsigned int nr_pending_queries;
    bool busy_polling;
    unsigned int polling_guard;
}
```
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
