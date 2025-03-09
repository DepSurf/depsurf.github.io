# Struct: <code>trace_iterator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    char * fmt;
    unsigned int fmt_size;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    char * fmt;
    unsigned int fmt_size;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    char * fmt;
    unsigned int fmt_size;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    char * fmt;
    unsigned int fmt_size;
    long int wait_index;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    char * fmt;
    unsigned int fmt_size;
    long int wait_index;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct array_buffer * array_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    void * temp;
    unsigned int temp_size;
    char * fmt;
    unsigned int fmt_size;
    long int wait_index;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
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
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
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
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct trace_iterator {
    struct trace_array * tr;
    struct tracer * trace;
    struct trace_buffer * trace_buffer;
    void * private;
    int cpu_file;
    struct mutex mutex;
    struct ring_buffer_iter * * buffer_iter;
    long unsigned int iter_flags;
    struct trace_seq tmp_seq;
    cpumask_var_t started;
    bool snapshot;
    struct trace_seq seq;
    struct trace_entry * ent;
    long unsigned int lost_events;
    int leftover;
    int ent_size;
    int cpu;
    u64 ts;
    loff_t pos;
    long int idx;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct array_buffer * array_buffer</code>
</li>
<li>
<b>Field added. </b>
<code>void * temp</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int temp_size</code>
</li>
<li>
<b>Field removed. </b>
<code>struct trace_buffer * trace_buffer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char * fmt</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int fmt_size</code>
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
<code>long int wait_index</code>
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
