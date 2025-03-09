# Struct: <code>x86_pmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    bool late_ack;
    unsigned int (*)(struct perf_event *, unsigned int) limit_period;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int free_running_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    atomic_t[3] lbr_exclusive;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    bool late_ack;
    unsigned int (*)(struct perf_event *, unsigned int) limit_period;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int free_running_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    bool late_ack;
    unsigned int (*)(struct perf_event *, unsigned int) limit_period;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int free_running_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    bool late_ack;
    unsigned int (*)(struct perf_event *, unsigned int) limit_period;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    long unsigned int attr_freeze_on_smi;
    struct attribute * * attrs;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int free_running_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    bool late_ack;
    unsigned int (*)(struct perf_event *, unsigned int) limit_period;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct attribute * * caps_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    long unsigned int attr_freeze_on_smi;
    struct attribute * * attrs;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int free_running_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    bool late_ack;
    u64 (*)(struct perf_event *, u64) limit_period;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct attribute * * caps_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    long unsigned int attr_freeze_on_smi;
    struct attribute * * attrs;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int large_pebs_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    struct attribute * * event_attrs;
    struct attribute * * caps_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    struct attribute * * cpu_events;
    long unsigned int attr_freeze_on_smi;
    struct attribute * * attrs;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    int pebs_record_size;
    int pebs_buffer_size;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    int max_pebs_events;
    long unsigned int large_pebs_flags;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int enabled_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int enabled_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    u64 (*)(struct perf_event *) update_topdown_event;
    int (*)(struct perf_event *) set_topdown_event_period;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int mid_ack;
    unsigned int enabled_ack;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    unsigned int pebs_block;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    int num_topdown_events;
    u64 (*)(struct perf_event *) update_topdown_event;
    int (*)(struct perf_event *) set_topdown_event_period;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int num_hybrid_pmus;
    struct x86_hybrid_pmu * hybrid_pmu;
    u8 (*)() get_hybrid_cpu_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int mid_ack;
    unsigned int enabled_ack;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    unsigned int pebs_block;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    int num_topdown_events;
    u64 (*)(struct perf_event *) update_topdown_event;
    int (*)(struct perf_event *) set_topdown_event_period;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int num_hybrid_pmus;
    struct x86_hybrid_pmu * hybrid_pmu;
    u8 (*)() get_hybrid_cpu_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *, int) assign;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int mid_ack;
    unsigned int enabled_ack;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    unsigned int pebs_block;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    u64 (*)(struct perf_event *, u64) pebs_latency_data;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_has_info;
    unsigned int lbr_has_tsx;
    unsigned int lbr_from_flags;
    unsigned int lbr_to_cycles;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    int num_topdown_events;
    u64 (*)(struct perf_event *) update_topdown_event;
    int (*)(struct perf_event *) set_topdown_event_period;
    void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
    int (*)(struct perf_event *) filter_match;
    int num_hybrid_pmus;
    struct x86_hybrid_pmu * hybrid_pmu;
    u8 (*)() get_hybrid_cpu_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *, int) assign;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) set_period;
    u64 (*)(struct perf_event *) update;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    void (*)(struct perf_event *, s64 *) limit_period;
    unsigned int late_ack;
    unsigned int mid_ack;
    unsigned int enabled_ack;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_pmu_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    unsigned int pebs_block;
    unsigned int pebs_ept;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    u64 (*)(struct perf_event *, u64) pebs_latency_data;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    u64 pebs_capable;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_has_info;
    unsigned int lbr_has_tsx;
    unsigned int lbr_from_flags;
    unsigned int lbr_to_cycles;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    int num_topdown_events;
    void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *, void *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
    void (*)(struct pmu *, int, bool *) filter;
    int num_hybrid_pmus;
    struct x86_hybrid_pmu * hybrid_pmu;
    u8 (*)() get_hybrid_cpu_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *, int) assign;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) set_period;
    u64 (*)(struct perf_event *) update;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    void (*)(struct perf_event *, s64 *) limit_period;
    unsigned int late_ack;
    unsigned int mid_ack;
    unsigned int enabled_ack;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_pmu_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    unsigned int pebs_block;
    unsigned int pebs_ept;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    u64 (*)(struct perf_event *, u64) pebs_latency_data;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    u64 pebs_capable;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_has_info;
    unsigned int lbr_has_tsx;
    unsigned int lbr_from_flags;
    unsigned int lbr_to_cycles;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    int num_topdown_events;
    void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *, void *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
    void (*)(struct pmu *, int, bool *) filter;
    int num_hybrid_pmus;
    struct x86_hybrid_pmu * hybrid_pmu;
    u8 (*)() get_hybrid_cpu_type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *, int) assign;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) set_period;
    u64 (*)(struct perf_event *) update;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    void (*)(struct perf_event *, s64 *) limit_period;
    unsigned int late_ack;
    unsigned int mid_ack;
    unsigned int enabled_ack;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_pmu_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    unsigned int pebs_block;
    unsigned int pebs_ept;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    u64 (*)(struct perf_event *, u64) pebs_latency_data;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    u64 pebs_capable;
    unsigned int lbr_tos;
    unsigned int lbr_from;
    unsigned int lbr_to;
    unsigned int lbr_info;
    unsigned int lbr_nr;
    u64 lbr_sel_mask;
    u64 lbr_ctl_mask;
    const int * lbr_sel_map;
    int * lbr_ctl_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    unsigned int lbr_has_info;
    unsigned int lbr_has_tsx;
    unsigned int lbr_from_flags;
    unsigned int lbr_to_cycles;
    unsigned int lbr_depth_mask;
    unsigned int lbr_deep_c_reset;
    unsigned int lbr_lip;
    unsigned int lbr_cpl;
    unsigned int lbr_filter;
    unsigned int lbr_call_stack;
    unsigned int lbr_mispred;
    unsigned int lbr_timed_lbr;
    unsigned int lbr_br_type;
    unsigned int lbr_counters;
    void (*)() lbr_reset;
    void (*)(struct cpu_hw_events *) lbr_read;
    void (*)(void *) lbr_save;
    void (*)(void *) lbr_restore;
    atomic_t[3] lbr_exclusive;
    int num_topdown_events;
    void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *, void *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
    void (*)(struct pmu *, int, bool *) filter;
    int num_hybrid_pmus;
    struct x86_hybrid_pmu * hybrid_pmu;
    enum hybrid_cpu_type (*)() get_hybrid_cpu_type;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
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
<code>unsigned int pebs_prec_dist</code>
</li>
<li>
<b>Field added. </b>
<code>bool lbr_pt_coexist</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int amd_nb_constraints</code>
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
<code>void (*)(struct perf_event *) add</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct perf_event *) del</code>
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
<code>long unsigned int attr_freeze_on_smi</code>
</li>
<li>
<b>Field added. </b>
<code>struct attribute * * attrs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pebs_no_tlb</code>
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
<code>struct attribute * * caps_attrs</code>
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
<code>void (*)(struct perf_event *) read</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int large_pebs_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int free_running_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(struct perf_event *, unsigned int) limit_period</code> ➡️ <code>u64 (*)(struct perf_event *, u64) limit_period</code>
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
<code>unsigned int counter_freezing</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct perf_event *, u64) check_period</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool late_ack</code> ➡️ <code>unsigned int late_ack</code>
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
<b>Field added. </b>
<code>unsigned int pebs_no_isolation</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rtm_abort_event</code>
</li>
<li>
<b>Field removed. </b>
<code>struct attribute * * event_attrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct attribute * * caps_attrs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct attribute * * cpu_events</code>
</li>
<li>
<b>Field removed. </b>
<code>struct attribute * * attrs</code>
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
<code>u64 perf_ctr_pair_en</code>
</li>
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
<code>unsigned int enabled_ack</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx</code>
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
<code>unsigned int lbr_info</code>
</li>
<li>
<b>Field added. </b>
<code>u64 lbr_ctl_mask</code>
</li>
<li>
<b>Field added. </b>
<code>int * lbr_ctl_map</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_depth_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_deep_c_reset</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_lip</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_cpl</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_filter</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_call_stack</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_mispred</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_timed_lbr</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_br_type</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)() lbr_reset</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct cpu_hw_events *) lbr_read</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *) lbr_save</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(void *) lbr_restore</code>
</li>
<li>
<b>Field added. </b>
<code>u64 (*)(struct perf_event *) update_topdown_event</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct perf_event *) set_topdown_event_period</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pt_regs *) drain_pebs</code> ➡️ <code>void (*)(struct pt_regs *, struct perf_sample_data *) drain_pebs</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int lbr_tos</code> ➡️ <code>unsigned int lbr_tos</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int lbr_from</code> ➡️ <code>unsigned int lbr_from</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int lbr_to</code> ➡️ <code>unsigned int lbr_to</code>
</li>
<li>
<b>Field type changed. </b>
<code>int lbr_nr</code> ➡️ <code>unsigned int lbr_nr</code>
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
<code>unsigned int mid_ack</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pebs_block</code>
</li>
<li>
<b>Field added. </b>
<code>int num_topdown_events</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct perf_event *) filter_match</code>
</li>
<li>
<b>Field added. </b>
<code>int num_hybrid_pmus</code>
</li>
<li>
<b>Field added. </b>
<code>struct x86_hybrid_pmu * hybrid_pmu</code>
</li>
<li>
<b>Field added. </b>
<code>u8 (*)() get_hybrid_cpu_type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int counter_freezing</code>
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
<code>void (*)(struct perf_event *, int) assign</code>
</li>
<li>
<b>Field added. </b>
<code>u64 (*)(struct perf_event *, u64) pebs_latency_data</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_has_info</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_has_tsx</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_from_flags</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int lbr_to_cycles</code>
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
<code>int (*)(struct perf_event *) set_period</code>
</li>
<li>
<b>Field added. </b>
<code>u64 (*)(struct perf_event *) update</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pebs_ept</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pebs_capable</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct pmu *, int, bool *) filter</code>
</li>
<li>
<b>Field removed. </b>
<code>int perfctr_second_write</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 (*)(struct perf_event *) update_topdown_event</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct perf_event *) set_topdown_event_period</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct perf_event *) filter_match</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 (*)(struct perf_event *, u64) limit_period</code> ➡️ <code>void (*)(struct perf_event *, s64 *) limit_period</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct perf_event_context *, bool) sched_task</code> ➡️ <code>void (*)(struct perf_event_pmu_context *, bool) sched_task</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct perf_event_context *, struct perf_event_context *) swap_task_ctx</code> ➡️ <code>void (*)(struct perf_event_pmu_context *, struct perf_event_pmu_context *) swap_task_ctx</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct perf_guest_switch_msr * (*)(int *) guest_get_msrs</code> ➡️ <code>struct perf_guest_switch_msr * (*)(int *, void *) guest_get_msrs</code>
</li>
</ul>
</details>
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
<code>unsigned int lbr_counters</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 (*)() get_hybrid_cpu_type</code> ➡️ <code>enum hybrid_cpu_type (*)() get_hybrid_cpu_type</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct x86_pmu {
    const char * name;
    int version;
    int (*)(struct pt_regs *) handle_irq;
    void (*)() disable_all;
    void (*)(int) enable_all;
    void (*)(struct perf_event *) enable;
    void (*)(struct perf_event *) disable;
    void (*)(struct perf_event *) add;
    void (*)(struct perf_event *) del;
    void (*)(struct perf_event *) read;
    int (*)(struct perf_event *) hw_config;
    int (*)(struct cpu_hw_events *, int, int *) schedule_events;
    unsigned int eventsel;
    unsigned int perfctr;
    int (*)(int, bool) addr_offset;
    int (*)(int) rdpmc_index;
    u64 (*)(int) event_map;
    int max_events;
    int num_counters;
    int num_counters_fixed;
    int cntval_bits;
    u64 cntval_mask;
    long unsigned int events_maskl;
    long unsigned int[1] events_mask;
    int events_mask_len;
    int apic;
    u64 max_period;
    struct event_constraint * (*)(struct cpu_hw_events *, int, struct perf_event *) get_event_constraints;
    void (*)(struct cpu_hw_events *, struct perf_event *) put_event_constraints;
    void (*)(struct cpu_hw_events *) start_scheduling;
    void (*)(struct cpu_hw_events *, int, int) commit_scheduling;
    void (*)(struct cpu_hw_events *) stop_scheduling;
    struct event_constraint * event_constraints;
    struct x86_pmu_quirk * quirks;
    int perfctr_second_write;
    u64 (*)(struct perf_event *, u64) limit_period;
    unsigned int late_ack;
    unsigned int counter_freezing;
    int attr_rdpmc_broken;
    int attr_rdpmc;
    struct attribute * * format_attrs;
    ssize_t (*)(char *, u64) events_sysfs_show;
    const struct attribute_group * * attr_update;
    long unsigned int attr_freeze_on_smi;
    int (*)(int) cpu_prepare;
    void (*)(int) cpu_starting;
    void (*)(int) cpu_dying;
    void (*)(int) cpu_dead;
    void (*)() check_microcode;
    void (*)(struct perf_event_context *, bool) sched_task;
    u64 intel_ctrl;
    union perf_capabilities intel_cap;
    unsigned int bts;
    unsigned int bts_active;
    unsigned int pebs;
    unsigned int pebs_active;
    unsigned int pebs_broken;
    unsigned int pebs_prec_dist;
    unsigned int pebs_no_tlb;
    unsigned int pebs_no_isolation;
    int pebs_record_size;
    int pebs_buffer_size;
    int max_pebs_events;
    void (*)(struct pt_regs *) drain_pebs;
    struct event_constraint * pebs_constraints;
    void (*)(struct perf_event *) pebs_aliases;
    long unsigned int large_pebs_flags;
    u64 rtm_abort_event;
    long unsigned int lbr_tos;
    long unsigned int lbr_from;
    long unsigned int lbr_to;
    int lbr_nr;
    u64 lbr_sel_mask;
    const int * lbr_sel_map;
    bool lbr_double_abort;
    bool lbr_pt_coexist;
    atomic_t[3] lbr_exclusive;
    unsigned int amd_nb_constraints;
    u64 perf_ctr_pair_en;
    struct extra_reg * extra_regs;
    unsigned int flags;
    struct perf_guest_switch_msr * (*)(int *) guest_get_msrs;
    int (*)(struct perf_event *, u64) check_period;
    int (*)(struct perf_event *) aux_output_match;
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
