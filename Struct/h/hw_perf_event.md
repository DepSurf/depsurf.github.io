# Struct: <code>hw_perf_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    int cqm_state;
    u32 cqm_rmid;
    int is_group_event;
    struct list_head cqm_events_entry;
    struct list_head cqm_groups_entry;
    struct list_head cqm_group_entry;
    int itrace_started;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    struct task_struct * target;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    int cqm_state;
    u32 cqm_rmid;
    int is_group_event;
    struct list_head cqm_events_entry;
    struct list_head cqm_groups_entry;
    struct list_head cqm_group_entry;
    int itrace_started;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    int cqm_state;
    u32 cqm_rmid;
    int is_group_event;
    struct list_head cqm_events_entry;
    struct list_head cqm_groups_entry;
    struct list_head cqm_group_entry;
    int itrace_started;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    int itrace_started;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct rhlist_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct rhlist_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct rhlist_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 saved_metric;
    u64 saved_slots;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
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
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
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
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hw_perf_event {
    u64 config;
    u64 last_tag;
    long unsigned int config_base;
    long unsigned int event_base;
    int event_base_rdpmc;
    int idx;
    int last_cpu;
    int flags;
    struct hw_perf_event_extra extra_reg;
    struct hw_perf_event_extra branch_reg;
    struct hrtimer hrtimer;
    struct list_head tp_list;
    u64 pwr_acc;
    u64 ptsc;
    struct arch_hw_breakpoint info;
    struct list_head bp_list;
    u8 iommu_bank;
    u8 iommu_cntr;
    u16 padding;
    u64 conf;
    u64 conf1;
    struct task_struct * target;
    void * addr_filters;
    long unsigned int addr_filters_gen;
    int state;
    local64_t prev_count;
    u64 sample_period;
    u64 last_period;
    local64_t period_left;
    u64 interrupts_seq;
    u64 interrupts;
    u64 freq_time_stamp;
    u64 freq_count_stamp;
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
<code>u64 pwr_acc</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ptsc</code>
</li>
<li>
<b>Field added. </b>
<code>void * addr_filters</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int addr_filters_gen</code>
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
<code>u8 iommu_bank</code>
</li>
<li>
<b>Field added. </b>
<code>u8 iommu_cntr</code>
</li>
<li>
<b>Field added. </b>
<code>u16 padding</code>
</li>
<li>
<b>Field added. </b>
<code>u64 conf</code>
</li>
<li>
<b>Field added. </b>
<code>u64 conf1</code>
</li>
<li>
<b>Field removed. </b>
<code>int cqm_state</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 cqm_rmid</code>
</li>
<li>
<b>Field removed. </b>
<code>int is_group_event</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head cqm_events_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head cqm_groups_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head cqm_group_entry</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int itrace_started</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 saved_metric</code>
</li>
<li>
<b>Field added. </b>
<code>u64 saved_slots</code>
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
<b>Field type changed. </b>
<code>struct list_head bp_list</code> ➡️ <code>struct rhlist_head bp_list</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct arch_hw_breakpoint info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head bp_list</code>
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
