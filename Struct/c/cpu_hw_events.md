# Struct: <code>cpu_hw_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    u64 pebs_enabled;
    int lbr_users;
    void * lbr_context;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    u64 pebs_enabled;
    int lbr_users;
    void * lbr_context;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int lbr_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int lbr_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int lbr_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int lbr_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int lbr_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] dirty;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] dirty;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] dirty;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    int brs_active;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] dirty;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    u64 fixed_ctrl_val;
    u64 active_fixed_ctrl_val;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    int brs_active;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] dirty;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    u64 fixed_ctrl_val;
    u64 active_fixed_ctrl_val;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    int brs_active;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
    struct pmu * pmu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] dirty;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int n_txn_pair;
    int n_txn_metric;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    u64 fixed_ctrl_val;
    u64 active_fixed_ctrl_val;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    u64[32] lbr_counters;
    struct er_account * lbr_sel;
    struct er_account * lbr_ctl;
    u64 br_sel;
    void * last_task_ctx;
    int last_log_id;
    int lbr_select;
    void * lbr_xsave;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    int n_metric;
    struct amd_nb * amd_nb;
    int brs_active;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
    struct pmu * pmu;
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpu_hw_events {
    int n_events;
    int n_percpu;
    int disabled;
    int n_added;
    int n_limited;
    u8 pmcs_enabled;
    struct perf_event *[8] event;
    u64[8] events;
    unsigned int[8] flags;
    long unsigned int[4] mmcr;
    struct perf_event *[2] limited_counter;
    u8[2] limited_hwidx;
    u64[64] alternatives;
    long unsigned int[64] amasks;
    long unsigned int[64] avalues;
    unsigned int txn_flags;
    int n_txn_start;
    u64 bhrb_filter;
    unsigned int bhrb_users;
    void * bhrb_context;
    struct perf_branch_stack bhrb_stack;
    struct perf_branch_entry[32] bhrb_entries;
    u64 ic_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cpu_hw_events {
    int n_events;
    struct perf_event *[2] events;
    void * platform;
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
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
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
<code>int n_pebs</code>
</li>
<li>
<b>Field added. </b>
<code>int n_large_pebs</code>
</li>
<li>
<b>Field removed. </b>
<code>void * lbr_context</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * ds_pebs_vaddr</code>
</li>
<li>
<b>Field added. </b>
<code>void * ds_bts_vaddr</code>
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
<b>Field added. </b>
<code>struct x86_perf_task_context * last_task_ctx</code>
</li>
<li>
<b>Field added. </b>
<code>int last_log_id</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tfa_shadow</code>
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
<code>u64 pebs_data_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>u64 active_pebs_data_cfg</code>
</li>
<li>
<b>Field added. </b>
<code>int pebs_record_size</code>
</li>
<li>
<b>Field added. </b>
<code>int lbr_pebs_users</code>
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
<code>int n_pebs_via_pt</code>
</li>
<li>
<b>Field added. </b>
<code>int pebs_output</code>
</li>
<li>
<b>Field added. </b>
<code>int n_pair</code>
</li>
</ul>
</details>
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
<code>int n_txn_pair</code>
</li>
<li>
<b>Field added. </b>
<code>int n_txn_metric</code>
</li>
<li>
<b>Field added. </b>
<code>struct er_account * lbr_ctl</code>
</li>
<li>
<b>Field added. </b>
<code>int lbr_select</code>
</li>
<li>
<b>Field added. </b>
<code>void * lbr_xsave</code>
</li>
<li>
<b>Field added. </b>
<code>int n_metric</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct x86_perf_task_context * last_task_ctx</code> ➡️ <code>void * last_task_ctx</code>
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
<code>long unsigned int[1] dirty</code>
</li>
<li>
<b>Field added. </b>
<code>struct pmu * pmu</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[1] running</code>
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
<code>int brs_active</code>
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
<code>u64 fixed_ctrl_val</code>
</li>
<li>
<b>Field added. </b>
<code>u64 active_fixed_ctrl_val</code>
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
<code>u64[32] lbr_counters</code>
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
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cpu_hw_events {
    struct perf_event *[64] events;
    long unsigned int[1] active_mask;
    long unsigned int[1] running;
    int enabled;
    int n_events;
    int n_added;
    int n_txn;
    int[64] assign;
    u64[64] tags;
    struct perf_event *[64] event_list;
    struct event_constraint *[64] event_constraint;
    int n_excl;
    unsigned int txn_flags;
    int is_fake;
    struct debug_store * ds;
    void * ds_pebs_vaddr;
    void * ds_bts_vaddr;
    u64 pebs_enabled;
    int n_pebs;
    int n_large_pebs;
    int n_pebs_via_pt;
    int pebs_output;
    u64 pebs_data_cfg;
    u64 active_pebs_data_cfg;
    int pebs_record_size;
    int lbr_users;
    int lbr_pebs_users;
    struct perf_branch_stack lbr_stack;
    struct perf_branch_entry[32] lbr_entries;
    struct er_account * lbr_sel;
    u64 br_sel;
    struct x86_perf_task_context * last_task_ctx;
    int last_log_id;
    u64 intel_ctrl_guest_mask;
    u64 intel_ctrl_host_mask;
    struct perf_guest_switch_msr[64] guest_switch_msrs;
    u64 intel_cp_status;
    struct intel_shared_regs * shared_regs;
    struct event_constraint * constraint_list;
    struct intel_excl_cntrs * excl_cntrs;
    int excl_thread_id;
    u64 tfa_shadow;
    struct amd_nb * amd_nb;
    u64 perf_ctr_virt_mask;
    int n_pair;
    void *[2] kfree_on_online;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int n_percpu</code>
</li>
<li>
<b>Field added. </b>
<code>int disabled</code>
</li>
<li>
<b>Field added. </b>
<code>int n_limited</code>
</li>
<li>
<b>Field added. </b>
<code>u8 pmcs_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_event *[8] event</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int[8] flags</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[4] mmcr</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_event *[2] limited_counter</code>
</li>
<li>
<b>Field added. </b>
<code>u8[2] limited_hwidx</code>
</li>
<li>
<b>Field added. </b>
<code>u64[64] alternatives</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[64] amasks</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[64] avalues</code>
</li>
<li>
<b>Field added. </b>
<code>int n_txn_start</code>
</li>
<li>
<b>Field added. </b>
<code>u64 bhrb_filter</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bhrb_users</code>
</li>
<li>
<b>Field added. </b>
<code>void * bhrb_context</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_branch_stack bhrb_stack</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_branch_entry[32] bhrb_entries</code>
</li>
<li>
<b>Field added. </b>
<code>u64 ic_init</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[1] active_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[1] running</code>
</li>
<li>
<b>Field removed. </b>
<code>int enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_txn</code>
</li>
<li>
<b>Field removed. </b>
<code>int[64] assign</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[64] tags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_event *[64] event_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct event_constraint *[64] event_constraint</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_excl</code>
</li>
<li>
<b>Field removed. </b>
<code>int is_fake</code>
</li>
<li>
<b>Field removed. </b>
<code>struct debug_store * ds</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ds_pebs_vaddr</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ds_bts_vaddr</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 pebs_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_pebs</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_large_pebs</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_pebs_via_pt</code>
</li>
<li>
<b>Field removed. </b>
<code>int pebs_output</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 pebs_data_cfg</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 active_pebs_data_cfg</code>
</li>
<li>
<b>Field removed. </b>
<code>int pebs_record_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int lbr_users</code>
</li>
<li>
<b>Field removed. </b>
<code>int lbr_pebs_users</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_branch_stack lbr_stack</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_branch_entry[32] lbr_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>struct er_account * lbr_sel</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 br_sel</code>
</li>
<li>
<b>Field removed. </b>
<code>struct x86_perf_task_context * last_task_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_log_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 intel_ctrl_guest_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 intel_ctrl_host_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_guest_switch_msr[64] guest_switch_msrs</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 intel_cp_status</code>
</li>
<li>
<b>Field removed. </b>
<code>struct intel_shared_regs * shared_regs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct event_constraint * constraint_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct intel_excl_cntrs * excl_cntrs</code>
</li>
<li>
<b>Field removed. </b>
<code>int excl_thread_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 tfa_shadow</code>
</li>
<li>
<b>Field removed. </b>
<code>struct amd_nb * amd_nb</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 perf_ctr_virt_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_pair</code>
</li>
<li>
<b>Field removed. </b>
<code>void *[2] kfree_on_online</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct perf_event *[64] events</code> ➡️ <code>u64[8] events</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * platform</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[1] active_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int[1] running</code>
</li>
<li>
<b>Field removed. </b>
<code>int enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_added</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_txn</code>
</li>
<li>
<b>Field removed. </b>
<code>int[64] assign</code>
</li>
<li>
<b>Field removed. </b>
<code>u64[64] tags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_event *[64] event_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct event_constraint *[64] event_constraint</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_excl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int txn_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>int is_fake</code>
</li>
<li>
<b>Field removed. </b>
<code>struct debug_store * ds</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ds_pebs_vaddr</code>
</li>
<li>
<b>Field removed. </b>
<code>void * ds_bts_vaddr</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 pebs_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_pebs</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_large_pebs</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_pebs_via_pt</code>
</li>
<li>
<b>Field removed. </b>
<code>int pebs_output</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 pebs_data_cfg</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 active_pebs_data_cfg</code>
</li>
<li>
<b>Field removed. </b>
<code>int pebs_record_size</code>
</li>
<li>
<b>Field removed. </b>
<code>int lbr_users</code>
</li>
<li>
<b>Field removed. </b>
<code>int lbr_pebs_users</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_branch_stack lbr_stack</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_branch_entry[32] lbr_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>struct er_account * lbr_sel</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 br_sel</code>
</li>
<li>
<b>Field removed. </b>
<code>struct x86_perf_task_context * last_task_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>int last_log_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 intel_ctrl_guest_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 intel_ctrl_host_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>struct perf_guest_switch_msr[64] guest_switch_msrs</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 intel_cp_status</code>
</li>
<li>
<b>Field removed. </b>
<code>struct intel_shared_regs * shared_regs</code>
</li>
<li>
<b>Field removed. </b>
<code>struct event_constraint * constraint_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct intel_excl_cntrs * excl_cntrs</code>
</li>
<li>
<b>Field removed. </b>
<code>int excl_thread_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 tfa_shadow</code>
</li>
<li>
<b>Field removed. </b>
<code>struct amd_nb * amd_nb</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 perf_ctr_virt_mask</code>
</li>
<li>
<b>Field removed. </b>
<code>int n_pair</code>
</li>
<li>
<b>Field removed. </b>
<code>void *[2] kfree_on_online</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct perf_event *[64] events</code> ➡️ <code>struct perf_event *[2] events</code>
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
