# Struct: <code>module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const long unsigned int * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const long unsigned int * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const long unsigned int * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const long unsigned int * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const long unsigned int * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    const struct tracepoint * * tracepoints_ptrs;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_enum_map * * trace_enums;
    unsigned int num_trace_enums;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp_alive;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const long unsigned int * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const long unsigned int * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const long unsigned int * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const long unsigned int * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const long unsigned int * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    const struct tracepoint * * tracepoints_ptrs;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_enum_map * * trace_enums;
    unsigned int num_trace_enums;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    const struct tracepoint * * tracepoints_ptrs;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_enum_map * * trace_enums;
    unsigned int num_trace_enums;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    const struct tracepoint * * tracepoints_ptrs;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    const struct tracepoint * * tracepoints_ptrs;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    const struct tracepoint * * tracepoints_ptrs;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    bool sig_ok;
    bool async_probe_requested;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    bool sig_ok;
    bool async_probe_requested;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    bool sig_ok;
    bool async_probe_requested;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    bool sig_ok;
    bool async_probe_requested;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    ctor_fn_t * ctors;
    unsigned int num_ctors;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    bool sig_ok;
    bool async_probe_requested;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_memory[7] mem;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    ctor_fn_t * ctors;
    unsigned int num_ctors;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
    struct _ddebug_info dyndbg_info;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    bool using_gplonly_symbols;
    bool sig_ok;
    bool async_probe_requested;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_memory[7] mem;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    void * noinstr_text_start;
    unsigned int noinstr_text_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int btf_data_size;
    void * btf_data;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    void * kprobes_text_start;
    unsigned int kprobes_text_size;
    long unsigned int * kprobe_blacklist;
    unsigned int num_kprobe_blacklist;
    int num_static_call_sites;
    struct static_call_site * static_call_sites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    ctor_fn_t * ctors;
    unsigned int num_ctors;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
    struct _ddebug_info dyndbg_info;
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
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[60] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
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
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct module {
    enum module_state state;
    struct list_head list;
    char[56] name;
    struct module_kobject mkobj;
    struct module_attribute * modinfo_attrs;
    const char * version;
    const char * srcversion;
    struct kobject * holders_dir;
    const struct kernel_symbol * syms;
    const s32 * crcs;
    unsigned int num_syms;
    struct mutex param_lock;
    struct kernel_param * kp;
    unsigned int num_kp;
    unsigned int num_gpl_syms;
    const struct kernel_symbol * gpl_syms;
    const s32 * gpl_crcs;
    const struct kernel_symbol * unused_syms;
    const s32 * unused_crcs;
    unsigned int num_unused_syms;
    unsigned int num_unused_gpl_syms;
    const struct kernel_symbol * unused_gpl_syms;
    const s32 * unused_gpl_crcs;
    bool sig_ok;
    bool async_probe_requested;
    const struct kernel_symbol * gpl_future_syms;
    const s32 * gpl_future_crcs;
    unsigned int num_gpl_future_syms;
    unsigned int num_exentries;
    struct exception_table_entry * extable;
    int (*)() init;
    struct module_layout core_layout;
    struct module_layout init_layout;
    struct mod_arch_specific arch;
    long unsigned int taints;
    unsigned int num_bugs;
    struct list_head bug_list;
    struct bug_entry * bug_table;
    struct mod_kallsyms * kallsyms;
    struct mod_kallsyms core_kallsyms;
    struct module_sect_attrs * sect_attrs;
    struct module_notes_attrs * notes_attrs;
    char * args;
    void * percpu;
    unsigned int percpu_size;
    unsigned int num_tracepoints;
    tracepoint_ptr_t * tracepoints_ptrs;
    unsigned int num_srcu_structs;
    struct srcu_struct * * srcu_struct_ptrs;
    unsigned int num_bpf_raw_events;
    struct bpf_raw_event_map * bpf_raw_events;
    struct jump_entry * jump_entries;
    unsigned int num_jump_entries;
    unsigned int num_trace_bprintk_fmt;
    const char * * trace_bprintk_fmt_start;
    struct trace_event_call * * trace_events;
    unsigned int num_trace_events;
    struct trace_eval_map * * trace_evals;
    unsigned int num_trace_evals;
    unsigned int num_ftrace_callsites;
    long unsigned int * ftrace_callsites;
    bool klp;
    bool klp_alive;
    struct klp_modinfo * klp_info;
    struct list_head source_list;
    struct list_head target_list;
    void (*)() exit;
    atomic_t refcnt;
    struct error_injection_entry * ei_funcs;
    unsigned int num_ei_funcs;
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
<code>bool klp</code>
</li>
<li>
<b>Field added. </b>
<code>struct klp_modinfo * klp_info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>const long unsigned int * crcs</code> ➡️ <code>const s32 * crcs</code>
</li>
<li>
<b>Field type changed. </b>
<code>const long unsigned int * gpl_crcs</code> ➡️ <code>const s32 * gpl_crcs</code>
</li>
<li>
<b>Field type changed. </b>
<code>const long unsigned int * unused_crcs</code> ➡️ <code>const s32 * unused_crcs</code>
</li>
<li>
<b>Field type changed. </b>
<code>const long unsigned int * unused_gpl_crcs</code> ➡️ <code>const s32 * unused_gpl_crcs</code>
</li>
<li>
<b>Field type changed. </b>
<code>const long unsigned int * gpl_future_crcs</code> ➡️ <code>const s32 * gpl_future_crcs</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int taints</code> ➡️ <code>long unsigned int taints</code>
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
<code>struct trace_eval_map * * trace_evals</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_trace_evals</code>
</li>
<li>
<b>Field removed. </b>
<code>struct trace_enum_map * * trace_enums</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_trace_enums</code>
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
<code>struct error_injection_entry * ei_funcs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_ei_funcs</code>
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
<code>unsigned int num_bpf_raw_events</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_raw_event_map * bpf_raw_events</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct tracepoint * * tracepoints_ptrs</code> ➡️ <code>tracepoint_ptr_t * tracepoints_ptrs</code>
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
<code>unsigned int num_srcu_structs</code>
</li>
<li>
<b>Field added. </b>
<code>struct srcu_struct * * srcu_struct_ptrs</code>
</li>
</ul>
</details>
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
<code>void * noinstr_text_start</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int noinstr_text_size</code>
</li>
<li>
<b>Field added. </b>
<code>void * kprobes_text_start</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int kprobes_text_size</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int * kprobe_blacklist</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_kprobe_blacklist</code>
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
<code>bool using_gplonly_symbols</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int btf_data_size</code>
</li>
<li>
<b>Field added. </b>
<code>void * btf_data</code>
</li>
<li>
<b>Field added. </b>
<code>int num_static_call_sites</code>
</li>
<li>
<b>Field added. </b>
<code>struct static_call_site * static_call_sites</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const struct kernel_symbol * unused_syms</code>
</li>
<li>
<b>Field removed. </b>
<code>const s32 * unused_crcs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_unused_syms</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_unused_gpl_syms</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct kernel_symbol * unused_gpl_syms</code>
</li>
<li>
<b>Field removed. </b>
<code>const s32 * unused_gpl_crcs</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct kernel_symbol * gpl_future_syms</code>
</li>
<li>
<b>Field removed. </b>
<code>const s32 * gpl_future_crcs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_gpl_future_syms</code>
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
<code>ctor_fn_t * ctors</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int num_ctors</code>
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
<code>struct module_memory[7] mem</code>
</li>
<li>
<b>Field added. </b>
<code>struct _ddebug_info dyndbg_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module_layout core_layout</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module_layout init_layout</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool klp</code>
</li>
<li>
<b>Field removed. </b>
<code>bool klp_alive</code>
</li>
<li>
<b>Field removed. </b>
<code>struct klp_modinfo * klp_info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct jump_entry * jump_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_jump_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>bool klp</code>
</li>
<li>
<b>Field removed. </b>
<code>bool klp_alive</code>
</li>
<li>
<b>Field removed. </b>
<code>struct klp_modinfo * klp_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct error_injection_entry * ei_funcs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_ei_funcs</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[56] name</code> ➡️ <code>char[60] name</code>
</li>
</ul>
</details>
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
<code>unsigned int num_bpf_raw_events</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_raw_event_map * bpf_raw_events</code>
</li>
<li>
<b>Field removed. </b>
<code>struct jump_entry * jump_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_jump_entries</code>
</li>
<li>
<b>Field removed. </b>
<code>bool klp</code>
</li>
<li>
<b>Field removed. </b>
<code>bool klp_alive</code>
</li>
<li>
<b>Field removed. </b>
<code>struct klp_modinfo * klp_info</code>
</li>
<li>
<b>Field removed. </b>
<code>struct error_injection_entry * ei_funcs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int num_ei_funcs</code>
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
