# Function: <code>on_each_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909808,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:591",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/profile.c:create_proc_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/idle/intel_idle.c:intel_idle_exit",
        "drivers/char/agp/generic.c:global_cache_flush",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909808,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939520,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:576",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939520,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970592,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:583",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970592,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975984,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:594",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975984,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022432,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:596",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022432,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076496,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:598",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mcheck/mce.c:set_bank",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:cpa_flush_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076496,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123808,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:596",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/alternative.c:text_poke_bp",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123808,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169360,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169360,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217296,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217296,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285584,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:694",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285584,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269104,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:831",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269104,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578868533,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:set_attr_rdpmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897936,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991669,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102488,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591195855,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164277,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182073,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194089,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279358,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579301717,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614343896,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366718,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579419774,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426447,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580147047,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580170917,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624952,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580757314,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585067509,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586677733,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:global_cache_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870021,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:set_attr_rdpmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900758,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008725,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126408,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592062166,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194997,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216154,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229321,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321998,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579349381,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615274258,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427518,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579483326,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490203,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290888,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580319412,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580796776,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580941090,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585514245,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225221,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:global_cache_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866941,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:set_attr_rdpmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905777,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026448,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160767,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593828854,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244067,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268578,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280297,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381613,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579411093,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617050399,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495837,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579562395,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579570289,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580499196,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580530837,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019287,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581181395,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586665301,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588533205,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:global_cache_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870029,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:set_attr_rdpmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919905,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055064,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210975,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299438,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303971,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331522,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345305,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458221,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579492997,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627693540,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579591821,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579669883,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678608,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754384,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580787011,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320103,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581497219,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587913525,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589978709,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:global_cache_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578867885,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:set_attr_rdpmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917102,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054968,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216518,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305566,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311155,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331381,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:amd_check_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340354,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354185,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579470573,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579505253,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619451236,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604365,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579683846,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579692464,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580837054,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870233,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414100,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581615219,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588187461,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590288373,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:global_cache_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578890157,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:set_attr_rdpmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939534,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080328,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245894,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336510,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579341907,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361678,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:amd_check_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370482,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384049,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500685,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579534901,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621747348,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:init_amd_nbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634093,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579718342,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726992,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926478,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960729,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522020,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581728213,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588479461,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590629509,
      "name": "on_each_cpu",
      "external": false,
      "loc": "include/linux/smp.h:69",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:global_cache_flush"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491456000,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/armv8_deprecated.c:register_insn_emulation",
        "arch/arm64/kernel/armv8_deprecated.c:update_insn_emulation_mode",
        "arch/arm64/kernel/armv8_deprecated.c:update_insn_emulation_mode",
        "virt/kvm/kvm_main.c:kvm_exit",
        "virt/kvm/kvm_main.c:kvm_reboot",
        "virt/kvm/kvm_main.c:kvm_create_vm",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "virt/kvm/arm/arm.c:kvm_arch_init",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_remove",
        "drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe",
        "drivers/firmware/arm_sdei.c:sdei_device_thaw",
        "drivers/firmware/arm_sdei.c:sdei_device_resume",
        "drivers/firmware/arm_sdei.c:sdei_device_suspend",
        "drivers/firmware/arm_sdei.c:sdei_event_disable",
        "drivers/firmware/arm_sdei.c:sdei_event_enable",
        "drivers/firmware/arm_sdei.c:sdei_platform_reset",
        "drivers/firmware/arm_sdei.c:sdei_mark_interface_broken"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491456000,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225442196,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/vfp/vfpmodule.c:vfp_init",
        "arch/arm/kernel/smp_tlb.c:flush_bp_all",
        "arch/arm/kernel/smp_tlb.c:flush_tlb_kernel_range",
        "arch/arm/kernel/smp_tlb.c:flush_tlb_kernel_page",
        "arch/arm/kernel/smp_tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225442196,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284406816,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:store_dscr_default",
        "arch/powerpc/kernel/setup_64.c:rfi_flush_enable",
        "arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me",
        "arch/powerpc/kernel/kvm.c:kvm_guest_init",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/mm/slice.c:slice_get_unmapped_area",
        "arch/powerpc/perf/imc-pmu.c:thread_imc_disable",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284406816,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271911830,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271911830,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
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
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186096,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186096,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133536,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133536,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177568,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177568,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void on_each_cpu(void (*)(void *) func, void * info, int wait)
```

```json
{
  "name": "on_each_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229776,
      "name": "on_each_cpu",
      "external": true,
      "loc": "kernel/smp.c:611",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/ftrace.c:run_sync",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events.c:ftrace_event_pid_write",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229776,
      "name": "on_each_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
<b>Param type changed. </b>
<code>void (*)(void *) func</code> ➡️ <code>smp_call_func_t func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void on_each_cpu(smp_call_func_t func, void * info, int wait)
```
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
