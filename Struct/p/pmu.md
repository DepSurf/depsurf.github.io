# Struct: <code>pmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *) event_mapped;
    void (*)(struct perf_event *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    u64 (*)(struct perf_event *) count;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct perf_event *) filter_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *) event_mapped;
    void (*)(struct perf_event *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    u64 (*)(struct perf_event *) count;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *) event_mapped;
    void (*)(struct perf_event *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    u64 (*)(struct perf_event *) count;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(int, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_pmu_context * cpu_pmu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_pmu_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    bool (*)(struct pmu *, int) filter;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    struct device * parent;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_pmu_context * cpu_pmu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_pmu_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    bool (*)(struct pmu *, int) filter;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    struct device * parent;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_pmu_context * cpu_pmu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_pmu_context *, bool) sched_task;
    struct kmem_cache * task_ctx_cache;
    void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    bool (*)(struct pmu *, int) filter;
    int (*)(struct perf_event *, u64) check_period;
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
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
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
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pmu {
    struct list_head entry;
    struct module * module;
    struct device * dev;
    const struct attribute_group * * attr_groups;
    const struct attribute_group * * attr_update;
    const char * name;
    int type;
    int capabilities;
    int * pmu_disable_count;
    struct perf_cpu_context * pmu_cpu_context;
    atomic_t exclusive_cnt;
    int task_ctx_nr;
    int hrtimer_interval_ms;
    unsigned int nr_addr_filters;
    void (*)(struct pmu *) pmu_enable;
    void (*)(struct pmu *) pmu_disable;
    int (*)(struct perf_event *) event_init;
    void (*)(struct perf_event *, struct mm_struct *) event_mapped;
    void (*)(struct perf_event *, struct mm_struct *) event_unmapped;
    int (*)(struct perf_event *, int) add;
    void (*)(struct perf_event *, int) del;
    void (*)(struct perf_event *, int) start;
    void (*)(struct perf_event *, int) stop;
    void (*)(struct perf_event *) read;
    void (*)(struct pmu *, unsigned int) start_txn;
    int (*)(struct pmu *) commit_txn;
    void (*)(struct pmu *) cancel_txn;
    int (*)(struct perf_event *) event_idx;
    void (*)(struct perf_event_context *, bool) sched_task;
    size_t task_ctx_size;
    void * (*)(struct perf_event *, void * *, int, bool) setup_aux;
    void (*)(void *) free_aux;
    int (*)(struct list_head *) addr_filters_validate;
    void (*)(struct perf_event *) addr_filters_sync;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int (*)(struct perf_event *, u64) check_period;
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
<code>unsigned int nr_addr_filters</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct list_head *) addr_filters_validate</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct perf_event *) addr_filters_sync</code>
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
<b>Field removed. </b>
<code>u64 (*)(struct perf_event *) count</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct perf_event *) event_mapped</code> ➡️ <code>void (*)(struct perf_event *, struct mm_struct *) event_mapped</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct perf_event *) event_unmapped</code> ➡️ <code>void (*)(struct perf_event *, struct mm_struct *) event_unmapped</code>
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
<code>int (*)(struct perf_event *, u64) check_period</code>
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
<code>const struct attribute_group * * attr_update</code>
</li>
<li>
<b>Field type changed. </b>
<code>void * (*)(int, void * *, int, bool) setup_aux</code> ➡️ <code>void * (*)(struct perf_event *, void * *, int, bool) setup_aux</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct perf_event *) aux_output_match</code>
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
<code>void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>long int (*)(struct perf_event *, struct perf_output_handle *, long unsigned int) snapshot_aux</code>
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
<code>struct kmem_cache * task_ctx_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t task_ctx_size</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct perf_cpu_pmu_context * cpu_pmu_context</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct pmu *, int) filter</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_cpu_context * pmu_cpu_context</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct perf_event *) filter_match</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct perf_event_context *, bool) sched_task</code> ➡️ <code>void (*)(struct perf_event_pmu_context *, bool) sched_task</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx</code> ➡️ <code>void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx</code>
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
<code>struct device * parent</code>
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
