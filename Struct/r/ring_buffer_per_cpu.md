# Struct: <code>ring_buffer_per_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64[5] event_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64[5] event_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64[5] event_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_lost;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64[5] event_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_lost;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64[5] event_stamp;
    u64 read_stamp;
    long unsigned int pages_removed;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    atomic_t resize_disabled;
    struct trace_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_lost;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    rb_time_t write_stamp;
    rb_time_t before_stamp;
    u64[5] event_stamp;
    u64 read_stamp;
    long unsigned int pages_removed;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
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
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
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
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ring_buffer_per_cpu {
    int cpu;
    atomic_t record_disabled;
    struct ring_buffer * buffer;
    raw_spinlock_t reader_lock;
    arch_spinlock_t lock;
    struct lock_class_key lock_key;
    struct buffer_data_page * free_page;
    long unsigned int nr_pages;
    unsigned int current_context;
    struct list_head * pages;
    struct buffer_page * head_page;
    struct buffer_page * tail_page;
    struct buffer_page * commit_page;
    struct buffer_page * reader_page;
    long unsigned int lost_events;
    long unsigned int last_overrun;
    long unsigned int nest;
    local_t entries_bytes;
    local_t entries;
    local_t overrun;
    local_t commit_overrun;
    local_t dropped_events;
    local_t committing;
    local_t commits;
    local_t pages_touched;
    local_t pages_read;
    long int last_pages_touch;
    size_t shortest_full;
    long unsigned int read;
    long unsigned int read_bytes;
    u64 write_stamp;
    u64 read_stamp;
    long int nr_pages_to_update;
    struct list_head new_pages;
    struct work_struct update_pages_work;
    struct completion update_done;
    struct rb_irq_work irq_work;
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
<b>Field type changed. </b>
<code>unsigned int nr_pages</code> ➡️ <code>long unsigned int nr_pages</code>
</li>
<li>
<b>Field type changed. </b>
<code>int nr_pages_to_update</code> ➡️ <code>long int nr_pages_to_update</code>
</li>
</ul>
</details>
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
<code>struct buffer_data_page * free_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int nest</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>local_t pages_touched</code>
</li>
<li>
<b>Field added. </b>
<code>local_t pages_read</code>
</li>
<li>
<b>Field added. </b>
<code>long int last_pages_touch</code>
</li>
<li>
<b>Field added. </b>
<code>size_t shortest_full</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t resize_disabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ring_buffer * buffer</code> ➡️ <code>struct trace_buffer * buffer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>rb_time_t before_stamp</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 write_stamp</code> ➡️ <code>rb_time_t write_stamp</code>
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
<code>u64[5] event_stamp</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>local_t pages_lost</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int pages_removed</code>
</li>
</ul>
</details>
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
