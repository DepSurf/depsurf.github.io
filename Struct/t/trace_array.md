# Struct: <code>trace_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[546] enter_syscall_files;
    struct trace_event_file *[546] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    int function_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    int function_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    int function_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[548] enter_syscall_files;
    struct trace_event_file *[548] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[440] enter_syscall_files;
    struct trace_event_file *[440] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[442] enter_syscall_files;
    struct trace_event_file *[442] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[447] enter_syscall_files;
    struct trace_event_file *[447] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int no_filter_buffering_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
    struct trace_func_repeats * last_func_repeats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[449] enter_syscall_files;
    struct trace_event_file *[449] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int no_filter_buffering_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
    struct trace_func_repeats * last_func_repeats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[451] enter_syscall_files;
    struct trace_event_file *[451] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int no_filter_buffering_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
    struct trace_func_repeats * last_func_repeats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[451] enter_syscall_files;
    struct trace_event_file *[451] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int no_filter_buffering_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
    struct trace_func_repeats * last_func_repeats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[452] enter_syscall_files;
    struct trace_event_file *[452] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    cpumask_var_t pipe_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int no_filter_buffering_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
    struct trace_func_repeats * last_func_repeats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct array_buffer array_buffer;
    struct array_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct dentry * d_max_latency;
    struct work_struct fsnotify_work;
    struct irq_work fsnotify_irqwork;
    struct trace_pid_list * filtered_pids;
    struct trace_pid_list * filtered_no_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[462] enter_syscall_files;
    struct trace_event_file *[462] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    const char * system_names;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct eventfs_inode * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    cpumask_var_t pipe_cpumask;
    int ref;
    int trace_ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct trace_pid_list * function_no_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int no_filter_buffering_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
    struct trace_func_repeats * last_func_repeats;
    bool ring_buffer_expanded;
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
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
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
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct trace_array {
    struct list_head list;
    char * name;
    struct trace_buffer trace_buffer;
    struct trace_buffer max_buffer;
    bool allocated_snapshot;
    long unsigned int max_latency;
    struct trace_pid_list * filtered_pids;
    arch_spinlock_t max_lock;
    int buffer_disabled;
    int sys_refcount_enter;
    int sys_refcount_exit;
    struct trace_event_file *[436] enter_syscall_files;
    struct trace_event_file *[436] exit_syscall_files;
    int stop_count;
    int clock_id;
    int nr_topts;
    bool clear_trace;
    int buffer_percent;
    unsigned int n_err_log_entries;
    struct tracer * current_trace;
    unsigned int trace_flags;
    unsigned char[32] trace_flags_index;
    unsigned int flags;
    raw_spinlock_t start_lock;
    struct list_head err_log;
    struct dentry * dir;
    struct dentry * options;
    struct dentry * percpu_dir;
    struct dentry * event_dir;
    struct trace_options * topts;
    struct list_head systems;
    struct list_head events;
    struct trace_event_file * trace_marker_file;
    cpumask_var_t tracing_cpumask;
    int ref;
    struct ftrace_ops * ops;
    struct trace_pid_list * function_pids;
    struct list_head func_probes;
    struct list_head mod_trace;
    struct list_head mod_notrace;
    int function_enabled;
    int time_stamp_abs_ref;
    struct list_head hist_vars;
    struct cond_snapshot * cond_snapshot;
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
<code>struct trace_pid_list * function_pids</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[546] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[548] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[546] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[548] exit_syscall_files</code>
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
<code>struct list_head func_probes</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mod_trace</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mod_notrace</code>
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
<code>bool clear_trace</code>
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
<code>struct trace_event_file * trace_marker_file</code>
</li>
<li>
<b>Field added. </b>
<code>int time_stamp_abs_ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head hist_vars</code>
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
<code>int buffer_percent</code>
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
<code>unsigned int n_err_log_entries</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head err_log</code>
</li>
<li>
<b>Field added. </b>
<code>struct cond_snapshot * cond_snapshot</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[548] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[436] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[548] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[436] exit_syscall_files</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct array_buffer array_buffer</code>
</li>
<li>
<b>Field added. </b>
<code>struct dentry * d_max_latency</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct fsnotify_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct irq_work fsnotify_irqwork</code>
</li>
<li>
<b>Field added. </b>
<code>struct trace_pid_list * filtered_no_pids</code>
</li>
<li>
<b>Field added. </b>
<code>int trace_ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct trace_pid_list * function_no_pids</code>
</li>
<li>
<b>Field removed. </b>
<code>struct trace_buffer trace_buffer</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_buffer max_buffer</code> ➡️ <code>struct array_buffer max_buffer</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[436] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[440] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[436] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[440] exit_syscall_files</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[440] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[442] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[440] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[442] exit_syscall_files</code>
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
<code>int no_filter_buffering_ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct trace_func_repeats * last_func_repeats</code>
</li>
<li>
<b>Field removed. </b>
<code>int time_stamp_abs_ref</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[442] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[447] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[442] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[447] exit_syscall_files</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[447] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[449] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[447] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[449] exit_syscall_files</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[449] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[451] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[449] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[451] exit_syscall_files</code>
</li>
</ul>
</details>
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
<code>cpumask_var_t pipe_cpumask</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[451] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[452] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[451] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[452] exit_syscall_files</code>
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
<code>const char * system_names</code>
</li>
<li>
<b>Field added. </b>
<code>bool ring_buffer_expanded</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[452] enter_syscall_files</code> ➡️ <code>struct trace_event_file *[462] enter_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct trace_event_file *[452] exit_syscall_files</code> ➡️ <code>struct trace_event_file *[462] exit_syscall_files</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dentry * event_dir</code> ➡️ <code>struct eventfs_inode * event_dir</code>
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
