# Function: <code>paravirt_write_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861277,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578871140,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578878777,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
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
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578899766,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:__rmid_read",
        "arch/x86/events/intel/cqm.c:update_sample",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_start",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912606,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915520,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "addr": 18446744071578919697,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923184,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923751,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "addr": 18446744071594970758,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579031016,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:do_arch_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079574,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098256,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108378,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:load_percpu_segment",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "addr": 18446744071579115516,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119477,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120793,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121158,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136062,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "addr": 18446744071579139063,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145539,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156461,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579161134,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171874,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184202,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211105,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212273,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227954,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253574,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303303,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150923,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152825,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_set_bit",
        "arch/x86/lib/msr.c:msr_clear_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535476,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:auto_demotion_disable",
        "drivers/idle/intel_idle.c:c1e_promotion_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750425,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882965,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585886888,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586164223,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:enable_pci_io_ecs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164867,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:137",
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
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861167,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578874036,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880105,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "addr": 18446744071578900939,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_start",
        "arch/x86/events/intel/cqm.c:update_sample",
        "arch/x86/events/intel/cqm.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912679,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921609,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097776,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111571,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "addr": 18446744071579115472,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120274,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120694,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121478,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147305,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161176,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211729,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_eoi_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213122,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_eoi_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228174,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253772,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302811,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446283,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856137,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:c1e_promotion_disable",
        "drivers/idle/intel_idle.c:auto_demotion_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586281094,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586287405,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586300675,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577520,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:enable_pci_io_ecs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579171,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:127",
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
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861151,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578874036,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578880169,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "addr": 18446744071578901131,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_start",
        "arch/x86/events/intel/cqm.c:update_sample",
        "arch/x86/events/intel/cqm.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913111,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921849,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074120,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095960,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110112,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "addr": 18446744071579113359,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579118978,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119398,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120427,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:clear_closid",
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_cbm_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123545,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:move_myself",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_update_closid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140070,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156521,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173631,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195881,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224834,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240587,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267267,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318219,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583573931,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995769,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586485510,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491629,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586507957,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759088,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763491,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860783,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578873285,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578879513,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "addr": 18446744071578897052,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915081,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066326,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101809,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "addr": 18446744071579107105,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111026,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111417,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111555,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr",
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114226,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:__intel_rdt_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123926,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138195,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154087,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171687,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194078,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579222594,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236536,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263891,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315579,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583612635,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043929,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586610054,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586616093,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586626055,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885968,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886752,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:118",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861375,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578874344,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881817,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578908476,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917433,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017414,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076693,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113296,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124434,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124823,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125971,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:cat_wrmsr",
        "arch/x86/kernel/cpu/intel_rdt.c:mba_wrmsr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127626,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:__intel_rdt_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138214,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153241,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_error_reporting",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159426,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168957,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189183,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209902,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252988,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280787,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338491,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858635,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308249,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093094,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098822,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587113405,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587374656,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375456,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863468,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578876251,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883369,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578910908,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919945,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020165,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579024181,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026746,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082012,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119689,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133026,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133710,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134838,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:__intel_rdt_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150068,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163807,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180481,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200543,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222068,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264361,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292152,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349851,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059195,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603081312,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "addr": 18446744071587391221,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587396806,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587412925,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679129,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:114",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875963,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:x86_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883129,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578912412,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921609,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022453,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579028229,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032928,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087468,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125163,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
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
      "addr": 18446744071579128544,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134578,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139810,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142542,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153295,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169857,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189935,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196278,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216500,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224604,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245738,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289032,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317192,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339618,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376795,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584143323,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604883571,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "addr": 18446744071587571173,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587576774,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587593133,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810217,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876711,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578884399,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578916903,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926633,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029989,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579035783,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040479,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097152,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134818,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
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
      "addr": 18446744071579139536,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140981,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145674,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147074,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151446,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154254,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155028,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165322,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182436,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202770,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209190,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229550,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237772,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259573,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262369,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305416,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332440,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333614,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354834,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392314,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333451,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584823919,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "addr": 18446744071587847029,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587852678,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587868517,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588116107,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:176",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877193,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578918951,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928601,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032309,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579038103,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042879,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099136,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136738,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
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
      "addr": 18446744071579141664,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143237,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147961,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149001,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154006,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156750,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157524,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167786,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184724,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205024,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211446,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231790,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239996,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261221,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263953,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295312,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309512,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333541,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337854,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359170,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395626,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584468123,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959663,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "addr": 18446744071588051845,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057494,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588073749,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321017,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881380,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578924183,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934409,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040885,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579049191,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053171,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111632,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153275,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    },
    {
      "addr": 18446744071579160401,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162328,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166216,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172487,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174832,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579175520,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ]
    },
    {
      "addr": 18446744071579184749,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205424,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225961,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232300,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239413,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252819,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263820,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609093158,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287384,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ]
    },
    {
      "addr": 18446744071579290964,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325184,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338442,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364821,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579367342,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state"
      ]
    },
    {
      "addr": 18446744071579385832,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434410,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585031867,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655201,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588914965,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588922547,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588940765,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
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
      "addr": 18446744071589081693,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource"
      ]
    },
    {
      "addr": 18446744071591141128,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591142059,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:170",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897776,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579040224,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579154560,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579174832,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579175520,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579286544,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579362976,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579366832,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585654912,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071589080560,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877460,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578923079,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578935593,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044005,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579052487,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056506,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive",
        "arch/x86/kernel/process_64.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591648867,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111472,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:update_pasid",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579134504,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150925,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    },
    {
      "addr": 18446744071579157425,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159443,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163464,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169015,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171072,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579171776,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ]
    },
    {
      "addr": 18446744071579180989,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200688,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219913,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225420,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231621,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245680,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256312,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267227,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612158020,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293752,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ]
    },
    {
      "addr": 18446744071579297012,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326819,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338447,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579366414,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state"
      ]
    },
    {
      "addr": 18446744071591266149,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433642,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585183755,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781409,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588927605,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934979,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588952789,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226139,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:168",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578893504,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579043344,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579120832,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579151808,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579171072,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579171776,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579292912,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579361872,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579365904,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585781120,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881212,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578927703,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940441,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046680,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579057703,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063464,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591592695,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118112,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579140776,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157234,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    },
    {
      "addr": 18446744071579164401,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166375,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614281488,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176183,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178160,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579178864,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579187615,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222393,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227820,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234165,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247680,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257752,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276252,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614298436,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296433,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ]
    },
    {
      "addr": 18446744071579299812,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329539,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342214,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579370798,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state"
      ]
    },
    {
      "addr": 18446744071591208457,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436458,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065707,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585662018,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588574820,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588815893,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588825373,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588841236,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175371,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578895952,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579046144,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579127232,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579158176,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579178160,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579178864,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579295584,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579366256,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579370352,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071585661696,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578884920,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578932663,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948041,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068952,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579077399,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084680,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592764519,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143568,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579167672,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186310,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    },
    {
      "addr": 18446744071579195121,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197591,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615205304,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210007,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212352,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579213056,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579222686,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261203,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266493,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273382,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288226,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298888,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318924,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615225268,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343738,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ]
    },
    {
      "addr": 18446744071579347340,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382189,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384403,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399654,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579432030,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_secondary_clock",
        "arch/x86/kernel/kvmclock.c:kvm_restore_sched_clock_state"
      ]
    },
    {
      "addr": 18446744071592082024,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480885,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500474,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585512415,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586140645,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250323,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509285,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589519386,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589537713,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592029017,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:185",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578897280,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579067296,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579152784,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579187600,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579212352,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579213056,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579342720,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579426976,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579431424,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071586140272,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578882663,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "addr": 18446744071578913154,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "caller_func": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578940897,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578956808,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093640,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579105223,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113609,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118173,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu",
        "arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579213279,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234059,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl",
        "arch/x86/kernel/cpu/bugs.c:write_spec_ctrl_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244241,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246748,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616978304,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260743,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263312,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579264128,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579273073,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313073,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319056,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326806,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342382,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:update_mba_bw",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354103,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377749,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616999555,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404707,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ]
    },
    {
      "addr": 18446744071579408909,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449907,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465553,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_offline",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:__sysvec_kvm_asyncpf_interrupt"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration"
      ]
    },
    {
      "addr": 18446744071579500781,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559921,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582129,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663039,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371801,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "addr": 18446744071590716364,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590718161,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "addr": 18446744071590993381,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590997570,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591003374,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591030008,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796809,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578901024,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579091456,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579194240,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579263312,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579264128,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579403520,
      "name": "paravirt_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579494464,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587371408,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578887862,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129541,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579144183,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152361,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157613,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293291,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "addr": 18446744071579304193,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306780,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311673,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322967,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326023,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327086,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336353,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378101,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385520,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392534,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411605,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424507,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454053,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627627147,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467153,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537763,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593909,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579667162,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579691470,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587910959,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620313,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "addr": 18446744071592387980,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592389908,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592700245,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592704898,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592711438,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592739528,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740841,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:191",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126944,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578885894,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129861,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579144791,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154563,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159773,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299791,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "addr": 18446744071579311377,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313933,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318825,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331147,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:amd_set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334583,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335644,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345233,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387471,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395152,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405462,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424005,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436459,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466245,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619383179,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479601,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547133,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579550499,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606613,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681103,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579705230,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184911,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908057,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "addr": 18446744071592817028,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592818980,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593131269,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593138738,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593148334,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593176632,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266809,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:193",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127264,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578908198,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156181,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579174583,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183873,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__wrgsbase_inactive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189085,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329342,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init_exception_handling",
        "arch/x86/kernel/cpu/common.c:syscall_init",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "addr": 18446744071579342129,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344909,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348841,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361419,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:amd_set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364663,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365564,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376081,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/amd.c:smca_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423536,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441905,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_domain_reconfigure_cdp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_cpu_closid_rmid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453589,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466043,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496309,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_update_lepubkeyhash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621678229,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579528429,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575405,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578083,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637477,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715551,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739886,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588476911,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204841,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "addr": 18446744071593565836,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593567209,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr_each"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593891794,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593902142,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593930584,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149497,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:195",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153168,
      "name": "paravirt_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877193,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578918951,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928601,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032661,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579038455,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043231,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099520,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137122,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
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
      "addr": 18446744071579142032,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143605,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148329,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149369,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154374,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157118,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157892,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168138,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184980,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203872,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210294,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230638,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238844,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259925,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262657,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305416,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329445,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333758,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355074,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391530,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436875,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909823,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "addr": 18446744071587676837,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682486,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695893,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924665,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877129,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578918887,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928537,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032245,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579038039,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042815,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099072,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136674,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
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
      "addr": 18446744071579141584,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143157,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147881,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148921,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153926,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156670,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157444,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167706,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184644,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204944,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211366,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231710,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239916,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261125,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263857,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305416,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329365,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333678,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354994,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391450,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419787,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911247,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "addr": 18446744071588007989,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588013638,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588029893,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258073,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877481,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071578919431,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929113,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/suspend.c:xen_vcpu_notify_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035813,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "caller_func": []
    },
    {
      "addr": 18446744071579041687,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046552,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103543,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141794,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
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
      "addr": 18446744071579146720,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148293,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_update_control_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153017,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154057,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159062,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161806,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162580,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172890,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189892,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210224,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216646,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237150,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245388,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266725,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269457,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301152,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313634,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337637,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342078,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363442,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399978,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525835,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017327,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "addr": 18446744071588123429,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588129110,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588145365,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393593,
      "name": "paravirt_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:164",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void paravirt_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```
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
