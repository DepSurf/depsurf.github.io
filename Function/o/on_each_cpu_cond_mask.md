# Function: <code>on_each_cpu_cond_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124064,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:670",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124064,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169568,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169568,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217504,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217504,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285360,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:761",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285360,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268880,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:898",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268880,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273056,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:1124",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/ldt.c:write_ldt",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set_work",
        "mm/slub.c:validate_store",
        "mm/slub.c:cpu_partial_store",
        "mm/slub.c:list_locations",
        "mm/slub.c:__kmem_cache_shrink",
        "mm/slub.c:__kmem_cache_shutdown",
        "fs/buffer.c:invalidate_bh_lrus",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273056,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580425040,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:1126",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/ldt.c:write_ldt",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all",
        "kernel/sched/membarrier.c:membarrier_private_expedited",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set",
        "fs/buffer.c:invalidate_bh_lrus",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425040,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647920,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:1145",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/ldt.c:write_ldt",
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
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/profile.c:write_profile",
        "kernel/profile.c:read_profile",
        "kernel/time/hrtimer.c:clock_was_set",
        "fs/buffer.c:invalidate_bh_lrus",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647920,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914912,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:1146",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/ldt.c:write_ldt",
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
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers",
        "kernel/time/hrtimer.c:clock_was_set",
        "fs/buffer.c:invalidate_bh_lrus",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914912,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000544,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:994",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/amd.c:amd_check_microcode",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers",
        "kernel/time/hrtimer.c:clock_was_set",
        "fs/buffer.c:invalidate_bh_lrus",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000544,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_cond_mask(smp_cond_func_t cond_func, smp_call_func_t func, void * info, bool wait, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096688,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:1014",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:set_attr_rdpmc",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:freeze_on_smi_store",
        "arch/x86/xen/suspend.c:xen_arch_suspend",
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/alternative.c:text_poke_bp_batch",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/umwait.c:max_time_store",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/cpu/amd.c:amd_check_microcode",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq",
        "arch/x86/kernel/amd_nb.c:init_amd_nbs",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_kernel_range",
        "arch/x86/mm/tlb.c:flush_tlb_all",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:cpa_flush_all",
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited",
        "kernel/profile.c:profile_discard_flip_buffers",
        "kernel/profile.c:profile_flip_buffers",
        "kernel/time/hrtimer.c:clock_was_set",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "fs/buffer.c:invalidate_bh_lrus",
        "arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus",
        "drivers/char/agp/generic.c:global_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096688,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491456360,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491456360,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225442884,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225442884,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284407232,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284407232,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271912090,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271912090,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186304,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186304,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133744,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133744,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177776,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177776,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```

```json
{
  "name": "on_each_cpu_cond_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230000,
      "name": "on_each_cpu_cond_mask",
      "external": true,
      "loc": "kernel/smp.c:683",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:native_flush_tlb_others",
        "kernel/smp.c:on_each_cpu_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230000,
      "name": "on_each_cpu_cond_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void on_each_cpu_cond_mask(bool (*)(int, void *) cond_func, smp_call_func_t func, void * info, bool wait, gfp_t gfp_flags, const struct cpumask * mask)
```
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
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>cond_func, func, info, wait, gfp_flags, mask</code> ➡️ <code>cond_func, func, info, wait, mask</code>
</li>
<li>
<b>Param type changed. </b>
<code>bool (*)(int, void *) cond_func</code> ➡️ <code>smp_cond_func_t cond_func</code>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
