# Function: <code>wrmsrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871140,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578876232,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578878777,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881950,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888056,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:__intel_pmu_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912606,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:perf_restore_debug_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914416,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915520,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920984,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923184,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923751,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939670,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946454,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948745,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031016,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079574,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098256,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108378,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:load_percpu_segment",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115990,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579121158,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136062,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139503,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184202,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211184,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212352,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227954,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234516,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253574,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272771,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303303,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535476,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:auto_demotion_disable",
        "drivers/idle/intel_idle.c:c1e_promotion_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164223,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:enable_pci_io_ecs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164867,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:162",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874036,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578876824,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880105,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578884543,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361515,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912679,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913344,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916033,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919345,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921609,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923767,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938520,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943382,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954132,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027169,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075487,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097776,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111571,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114815,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579121478,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138946,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139739,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161176,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184702,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211808,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579213122,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228174,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235558,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253772,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271993,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302808,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856137,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:c1e_promotion_disable",
        "drivers/idle/intel_idle.c:auto_demotion_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586300675,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577520,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:enable_pci_io_ecs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579171,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:161",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874036,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578876840,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880169,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578884607,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379339,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913111,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913776,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916499,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919649,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921849,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578924151,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939048,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943910,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578949229,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024214,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026841,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074120,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095960,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110112,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113359,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579120427,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_cbm_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120854,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579140070,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146146,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147104,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173631,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195881,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196206,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223504,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224834,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240587,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248002,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267267,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287433,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318216,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995769,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586485272,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586507957,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759088,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763491,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873285,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578876152,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578879513,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883282,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897049,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906519,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578907197,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578909908,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912973,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915081,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917281,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932264,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578936998,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942141,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016598,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019198,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066326,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:set_cpuid_faulting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087825,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101809,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107105,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111555,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr",
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114390,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579138195,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144514,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145570,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171687,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194078,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194942,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221248,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222594,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236536,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243820,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263891,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284373,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315576,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043929,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609816,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586626055,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885968,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886752,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:152",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578874344,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578877304,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881817,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885122,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895322,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    },
    {
      "addr": 18446744071578908476,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578909149,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911858,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914526,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917433,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919142,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938542,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939174,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950301,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960460,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017414,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022618,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076693,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098632,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113296,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120259,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125971,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr",
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130582,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579153241,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init"
      ]
    },
    {
      "addr": 18446744071579159426,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160497,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189183,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209902,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211729,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238533,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240144,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252988,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259436,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280787,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303061,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338488,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308249,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092856,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587113405,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587374656,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375456,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578888784,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579142720,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579278576,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876251,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578879240,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883369,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886363,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897175,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ]
    },
    {
      "addr": 18446744071578910908,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911568,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914485,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917166,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919945,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921078,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941463,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942085,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952189,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963036,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020165,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579024415,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026746,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082012,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculative_store_bypass_update",
        "arch/x86/kernel/process.c:speculative_store_bypass_update",
        "arch/x86/kernel/process.c:speculative_store_bypass_update",
        "arch/x86/kernel/process.c:speculative_store_bypass_update",
        "arch/x86/kernel/process.c:speculative_store_bypass_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104168,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119689,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122176,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127902,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134838,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr",
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136933,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150068,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163807,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170850,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176240,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200543,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222068,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224705,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250810,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252637,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264361,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270645,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292152,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314962,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349851,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603081312,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587391009,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587412925,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678517,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679129,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:148",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578890688,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579019840,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579289904,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578875963,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578878952,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883129,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886155,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897418,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578912412,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913072,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916117,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578918830,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921609,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922870,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943375,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578944117,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954733,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961132,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022453,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579028463,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032928,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087468,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109800,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125425,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128544,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579134578,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153295,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160290,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161750,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189935,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196278,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198389,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216500,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245738,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248401,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274842,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276445,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289032,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294901,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317192,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318388,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579339618,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376795,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604883571,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587570972,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587593133,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809605,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810217,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578890608,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579021520,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579127040,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579314144,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579317824,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876711,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881121,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578884399,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578887420,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578899530,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578916903,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917617,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921331,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923809,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926633,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578927907,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948981,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578949717,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961757,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968140,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029989,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579036015,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040479,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097152,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119710,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135070,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139536,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579145674,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147074,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165322,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172370,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173861,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202770,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209190,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217045,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229550,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259573,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    },
    {
      "addr": 18446744071579262369,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289224,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290861,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305416,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311326,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332440,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579333614,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579354834,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392314,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584823919,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846831,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868517,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605124036,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115077,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116107,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:210",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578891840,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579029184,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579136816,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579258320,
      "name": "wrmsrl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579329280,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333072,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877193,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881923,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885407,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888892,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900858,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578918951,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919601,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923299,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925777,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928601,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929363,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951413,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952149,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964189,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970572,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032309,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579038335,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042879,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099136,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121598,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136990,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141664,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579147961,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149001,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149522,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167786,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174818,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176277,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205024,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211446,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213269,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231790,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261221,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    },
    {
      "addr": 18446744071579263953,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293149,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295312,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296845,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309512,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315470,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333541,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579337854,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579359170,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395626,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959663,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588051647,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073749,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605164259,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320773,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321017,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892880,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031440,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579138736,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579259968,
      "name": "wrmsrl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579333328,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579337312,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881380,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578887795,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889967,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578893618,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905197,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_commit_scheduling",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578924183,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578924833,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929635,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931443,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934409,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937072,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578957909,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578959685,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971725,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974126,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980076,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040885,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049135,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053171,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111632,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121698,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136472,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152791,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157136,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162328,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166216,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:switch_to_sld",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:init_intel_misc_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166937,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167346,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184749,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_clear_state",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192898,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197730,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203819,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225961,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232470,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239413,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252819,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609093158,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288352,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290964,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322125,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325184,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326765,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338442,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345490,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364821,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367594,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385832,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434410,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655201,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912254,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588940765,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609434036,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591141128,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591142059,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:204",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877460,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883315,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885759,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889453,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900253,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:icl_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_fixed",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_commit_scheduling",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923079,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923729,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926980,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932627,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578935593,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938256,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578959189,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960949,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973613,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976846,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982236,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044005,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052431,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056506,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591648867,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111472,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124044,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:update_pasid",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134504,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150441,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154352,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159443,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163464,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:switch_to_sld",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:init_intel_misc_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163625,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164034,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180989,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188690,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193378,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199083,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219913,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225590,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231621,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245680,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267227,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612158020,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591259239,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297012,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324813,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326819,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328365,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338447,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343558,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363845,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366666,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591266149,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433642,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781409,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588924686,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952789,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612508608,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591225208,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226139,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:202",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881212,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885825,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888719,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891904,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905067,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_commit_scheduling",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578927703,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928373,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934722,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937378,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940441,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943085,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964229,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966053,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979037,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982741,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985934,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991324,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046680,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057639,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063464,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591592695,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118112,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128073,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140776,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156785,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161696,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166375,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614281488,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:switch_to_sld",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170937,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171346,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187615,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195042,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198898,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222393,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227990,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234165,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247680,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276252,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614298436,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591202368,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299812,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327533,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329539,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331069,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342214,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367557,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370986,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591208457,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436458,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585662018,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588572801,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813278,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588841236,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614650865,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591174440,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175371,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578884920,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578890193,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578893173,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578907730,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_tfa_commit_scheduling",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932663,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933365,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940466,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578944241,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948041,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954743,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976773,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978597,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994214,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998453,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001902,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008380,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068952,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077335,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084680,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592764519,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143568,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153969,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167672,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186310,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192256,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197591,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615205304,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:switch_to_sld",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204185,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204722,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222686,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230274,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234754,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261203,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266566,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273382,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288226,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318924,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615225268,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592073329,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579347340,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382189,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384403,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386317,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399654,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579428453,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432218,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592082024,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480885,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500474,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586140645,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589247662,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589506318,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589537713,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615609803,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592027960,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592029017,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:219",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578882663,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889097,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_cpu_starting",
        "arch/x86/events/amd/core.c:amd_pmu_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891368,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb",
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_disable",
        "arch/x86/events/amd/brs.c:amd_brs_enable_all",
        "arch/x86/events/amd/brs.c:amd_brs_reset",
        "arch/x86/events/amd/brs.c:amd_brs_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578896274,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593806866,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940897,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941763,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578949558,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952790,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578956808,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965097,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988933,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991557,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010646,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579014677,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018534,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026000,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093640,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105127,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113609,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118173,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179131,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187975,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191971,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:os_xrstor_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197378,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213279,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234059,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment",
        "arch/x86/kernel/cpu/common.c:cet_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235318,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:write_spec_ctrl_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246748,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616978304,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254453,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255073,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273073,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281281,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286019,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313073,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317878,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326806,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342382,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377749,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616999555,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593839817,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408909,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447341,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449907,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452061,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465553,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497557,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500781,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593849547,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559921,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582129,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371801,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590714078,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590718161,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590990019,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590997570,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591030008,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617419777,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593795279,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796809,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887862,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897049,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901527,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901736,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb",
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_disable",
        "arch/x86/events/amd/brs.c:amd_brs_enable_all",
        "arch/x86/events/amd/brs.c:amd_brs_reset",
        "arch/x86/events/amd/brs.c:amd_brs_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578908627,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931122,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578957777,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958819,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965905,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969449,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_set_period"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973752,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982521,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008677,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011669,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035638,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041861,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046166,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054528,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129541,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144071,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152361,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157613,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234043,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243903,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248116,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:os_xrstor_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252878,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269535,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293291,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base",
        "arch/x86/kernel/cpu/common.c:cet_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300380,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306780,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311673,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316261,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316929,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336353,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346401,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352266,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378101,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384182,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392534,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424342,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454053,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627627147,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467153,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:cpu_emergency_svm_disable",
        "arch/x86/kernel/reboot.c:cpu_emergency_svm_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486480,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490589,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534221,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537763,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540253,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593909,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597629,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634430,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667162,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579691470,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620313,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_ibrs",
        "drivers/idle/intel_idle.c:intel_idle_ibrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592385518,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592389908,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592699761,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592704898,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592739528,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628173563,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595738751,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740841,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:225",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885894,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895161,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578899431,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900765,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906048,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929170,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578956961,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958004,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965137,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968673,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_set_period"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973000,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981833,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008709,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011717,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035894,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042101,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046183,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054432,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129861,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144679,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154563,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159773,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239931,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250255,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254976,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:os_xrstor_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260815,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275855,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299791,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base",
        "arch/x86/kernel/cpu/common.c:cet_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306684,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313933,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318825,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323397,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324065,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345233,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355281,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361226,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387471,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393580,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405462,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436294,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466245,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619383179,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479601,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:cpu_emergency_svm_disable",
        "arch/x86/kernel/reboot.c:cpu_emergency_svm_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498589,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502716,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547133,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579550499,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552621,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606613,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610413,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648478,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681103,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705230,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908057,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592814473,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592818980,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593130673,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593138738,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593176632,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596264735,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266809,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:227",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578908198,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:perf_clear_dirty_counters",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917433,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_disable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_enable_virt",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event",
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922023,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923357,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928384,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952386,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:handle_pmi_common",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:intel_update_topdown_event",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:icl_set_topdown_event_period",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack",
        "arch/x86/events/intel/core.c:intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980353,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981344,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578989665,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset_32",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993446,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_set_period"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997768,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008874,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033637,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036645,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062214,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067349,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071516,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079952,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156181,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174471,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183873,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189085,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug",
        "arch/x86/kernel/traps.c:exc_general_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271584,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279679,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd",
        "arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284952,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:os_xrstor_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290607,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305663,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329342,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base",
        "arch/x86/kernel/cpu/common.c:cet_disable",
        "arch/x86/kernel/cpu/common.c:cet_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337692,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:bhi_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344909,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348841,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/intel.c:splitlock_cpu_offline",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable",
        "arch/x86/kernel/cpu/intel.c:__split_lock_reenable_unlock",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353301,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353969,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376081,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385217,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_claim_bank",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391098,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422188,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441905,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465878,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496309,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621678229,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579528429,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533244,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575405,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578083,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581325,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637477,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579640173,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676042,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/shstk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/shstk.c:shstk_prctl",
        "arch/x86/kernel/shstk.c:shstk_prctl",
        "arch/x86/kernel/shstk.c:wrss_control",
        "arch/x86/kernel/shstk.c:restore_signal_shadow_stack",
        "arch/x86/kernel/shstk.c:setup_signal_shadow_stack",
        "arch/x86/kernel/shstk.c:shstk_setup",
        "arch/x86/kernel/shstk.c:shstk_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682334,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715551,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739886,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204841,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593563369,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593567209,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_do_enable",
        "drivers/thermal/intel/intel_hfi.c:hfi_do_enable",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:hfi_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593884180,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr_each"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593891794,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593930584,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_hwp_update",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597147423,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149497,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:229",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877193,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881923,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885407,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888892,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900858,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578918951,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919601,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923299,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925777,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928601,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929363,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951413,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952149,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964189,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970876,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032661,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579038687,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043231,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099520,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121982,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137374,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142032,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579148329,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149369,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149890,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168138,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175074,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176533,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203872,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210294,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212117,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230638,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259925,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    },
    {
      "addr": 18446744071579262657,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291120,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292653,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305416,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311374,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329445,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579333758,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579355074,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391530,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909823,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587676639,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695893,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605054031,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924421,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924665,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892880,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031792,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579139104,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579258672,
      "name": "wrmsrl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579329232,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333216,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871013,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578877181,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578879727,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883057,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895008,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914439,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915208,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919404,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922212,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925346,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925984,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948845,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950485,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961908,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964629,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972616,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976287,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031953,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053938,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068123,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073264,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079234,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080880,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081310,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099745,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107244,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111632,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138817,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145187,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154312,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165885,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195408,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198074,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226378,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228129,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239861,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245877,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266085,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268228,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287334,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321101,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816304,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587452733,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587472989,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605020077,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587556382,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/vmbus_drv.c:vmbus_isr",
        "drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587560322,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/hv/hv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574903,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:vmbus_initiate_unload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640383,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641209,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:281",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877129,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881859,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885343,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888828,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900794,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578918887,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919537,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923235,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925713,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928537,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929299,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951349,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952085,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964125,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970508,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032245,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579038271,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042815,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099072,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121534,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136926,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141584,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579147881,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148921,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149442,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167706,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174738,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176197,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204944,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211366,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213189,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231710,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261125,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    },
    {
      "addr": 18446744071579263857,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292320,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293853,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305416,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311294,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329365,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579333678,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579354994,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391450,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911247,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588007791,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029893,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605140606,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588257829,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258073,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578892816,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579031376,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579138656,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579259872,
      "name": "wrmsrl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579329152,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579333136,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```

```json
{
  "name": "wrmsrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877481,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578882211,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578885695,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888716,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901258,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578919431,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920081,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923779,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926257,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929113,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929875,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951925,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952661,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964717,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971100,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035813,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579041919,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046552,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103543,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126654,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142046,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146720,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579153017,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154057,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154578,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172890,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179922,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181381,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210224,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216646,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218469,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237150,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266725,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target"
      ]
    },
    {
      "addr": 18446744071579269457,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298989,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301152,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302685,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313634,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319614,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337637,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579342078,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579363442,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399978,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017327,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123231,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588145365,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605168453,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393349,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393593,
      "name": "wrmsrl",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:198",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578893296,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579034944,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579143792,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579265472,
      "name": "wrmsrl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579337440,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579341440,
      "name": "wrmsrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void wrmsrl(unsigned int msr, u64 val)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
