# Function: <code>paravirt_read_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871067,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578882329,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594957818,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/msr.c:msr_event_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354803,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:check_msr",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578899807,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:__rmid_read",
        "arch/x86/events/intel/cqm.c:update_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906186,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cstate.c:cstate_pmu_event_update",
        "arch/x86/events/intel/cstate.c:cstate_probe_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912556,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914378,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915482,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920672,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923146,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923980,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929437,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/rapl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/rapl.c:rapl_event_update",
        "arch/x86/events/intel/rapl.c:__rapl_pmu_event_start",
        "arch/x86/events/intel/rapl.c:rapl_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937309,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939782,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948729,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594969970,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594989189,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030093,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:do_arch_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595004424,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076242,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:try_msr_calibrate_tsc",
        "arch/x86/kernel/tsc_msr.c:try_msr_calibrate_tsc",
        "arch/x86/kernel/tsc_msr.c:try_msr_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078342,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:amd_e400_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098156,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107636,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:__print_cpu_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115191,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117122,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120778,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125584,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136032,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138929,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145556,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595013031,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154854,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595017446,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160871,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169382,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:read_hv_clock",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171671,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356839,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595040771,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595044304,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207087,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/msi.c:irq_msi_compose_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209693,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211217,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212385,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227971,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234496,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251682,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271973,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303433,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150831,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu",
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152726,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_set_bit",
        "arch/x86/lib/msr.c:msr_clear_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583535418,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:auto_demotion_disable",
        "drivers/idle/intel_idle.c:c1e_promotion_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583752272,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583755691,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584341489,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882951,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585886593,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585896854,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func",
        "drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func",
        "drivers/cpufreq/intel_pstate.c:intel_hwp_timer_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595331084,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164170,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:enable_pci_io_ecs",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586164616,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:132",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874265,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595120924,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886102,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595123129,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900597,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:update_sample",
        "arch/x86/events/intel/cqm.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911171,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913305,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916302,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
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
      "addr": 18446744071595128313,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921594,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922221,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933878,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578936539,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945766,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595152337,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028705,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072884,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074339,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:amd_e400_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097705,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110166,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579116023,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579116866,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120682,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133640,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138931,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139828,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147032,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595177675,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155206,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595183360,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161218,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595187254,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:read_hv_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595202761,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210894,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211841,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213025,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228191,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235543,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250751,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271855,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302787,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446204,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856122,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:c1e_promotion_disable",
        "drivers/idle/intel_idle.c:auto_demotion_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082024,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586281062,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586287308,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586300305,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577498,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:enable_pci_io_ecs",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586578860,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:122",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874265,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595363670,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886166,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595365916,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900789,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/cqm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/cqm.c:update_sample",
        "arch/x86/events/intel/cqm.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911619,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913737,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916606,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595371121,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921834,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922461,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934342,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937067,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946230,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024438,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hypercall_page_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:read_hv_clock_msr",
        "arch/x86/hyperv/hv_init.c:read_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595395045,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028425,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:do_arch_prctl",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595410665,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072280,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595411685,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095897,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108698,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114631,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115570,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119386,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595417636,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579140712,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146131,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147204,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156248,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595420887,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164502,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595426572,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170953,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595430115,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194727,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595445663,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222558,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223537,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224737,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240604,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247987,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264303,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287295,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318195,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583573852,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995753,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224604,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586485478,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586491532,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586508143,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759066,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763180,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873514,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596281918,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578887366,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596284366,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578904963,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578907154,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578910043,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596289264,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915066,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915725,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578927350,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930283,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939302,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579016822,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hypercall_page_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:read_hv_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596314325,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020745,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596330093,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579064381,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596331199,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087785,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100397,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102922,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106700,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107698,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596337054,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579123945,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138889,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144499,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145483,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153800,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596340988,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164358,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596346747,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170761,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175231,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596350508,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192967,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596366418,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220254,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221281,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222497,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236553,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243805,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260991,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284239,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315555,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018501,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583612556,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043913,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584296725,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586610022,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586615996,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586632491,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_pid",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885946,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886428,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874577,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602598195,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888614,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602600716,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578906931,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578909106,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911979,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602606052,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917418,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917581,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929446,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937723,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950982,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960345,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579017222,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hypercall_page_setup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:read_hv_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602632080,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024137,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602648283,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073373,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602649390,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098569,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111538,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115170,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119873,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120946,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124811,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602655225,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579138233,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153873,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159411,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160407,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168664,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602659121,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179062,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602664842,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186169,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190398,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602668692,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208826,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602684845,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236910,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237777,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238961,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253005,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259421,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277839,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302927,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338467,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065445,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583858556,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308233,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584695666,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587093062,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098783,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587115243,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587374634,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375072,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588820417,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/lib/insn-eval.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876385,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602766527,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578890490,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602769092,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578909315,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911529,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914625,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602774381,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919925,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602775326,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932325,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578940827,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943825,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962921,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579021149,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:read_hv_clock_msr",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024149,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602801817,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028303,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602818239,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077656,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602819346,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104105,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118050,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602824535,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123122,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127593,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129372,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133365,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602826392,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147993,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/intel_rdt_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164438,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170835,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176183,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180217,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602830469,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190629,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602836125,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197609,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202152,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602839980,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220856,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602856283,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249470,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250336,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251472,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264378,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270630,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289087,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314814,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349830,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580122848,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584059132,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603080714,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584922018,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587391189,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587396767,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603180883,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678485,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678804,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198717,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:109",
      "file": "arch/x86/lib/insn-eval.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876097,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604560766,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578890330,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604563605,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578910803,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913033,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916257,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604569213,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921589,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604570158,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578934133,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942747,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945825,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961017,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579022989,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:read_hv_clock_msr",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579028197,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029908,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604596861,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033971,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604613378,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082392,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604614490,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109737,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123711,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604619712,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129778,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134267,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136108,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141451,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142197,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153926,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160275,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161687,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169593,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604624445,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180037,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604630111,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187113,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191336,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604634184,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214425,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604636410,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244552,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604653214,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273278,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274144,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275280,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289049,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294886,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313301,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339470,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376774,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580169984,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584143260,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604882976,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585025922,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587571141,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587576735,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604991103,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809573,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809892,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589440061,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/lib/insn-eval.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876837,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881062,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604654787,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891562,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604657536,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915214,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917577,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921463,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604663790,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926613,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604664744,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578939701,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948363,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950966,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578962225,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968025,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579030557,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035717,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037554,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604692415,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041476,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604709263,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579092057,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710351,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119641,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133324,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604716625,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139970,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604718480,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145035,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147045,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147460,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153414,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153909,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154709,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166023,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172355,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173798,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182169,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604721626,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192613,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604727306,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199819,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204208,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604731415,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227433,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733693,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258632,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604752263,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287644,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288496,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289648,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305433,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311311,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328421,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354686,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392294,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215878,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333388,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584823904,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585229677,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846997,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587852639,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605102989,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605124015,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115045,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115412,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589898099,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:171",
      "file": "arch/x86/lib/insn-eval.c",
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877390,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881862,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604667186,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578892602,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604669946,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916974,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919561,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923431,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676288,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928581,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604677242,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942181,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950795,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953398,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964657,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970457,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579032877,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038037,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039954,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604704766,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043876,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604721663,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094041,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722751,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121529,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135212,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729283,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142194,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604731291,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147291,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148981,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149493,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149908,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155939,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157205,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168487,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174803,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176214,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184457,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734750,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194885,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604740431,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202043,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206464,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604744528,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229657,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604747077,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260280,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604765668,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290636,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291488,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294384,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295616,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309529,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315455,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332469,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579359022,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395606,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580264278,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584468060,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959648,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585366221,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588051813,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057455,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605142404,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605164228,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588320741,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321892,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590124083,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/insn-eval.c",
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
u64 paravirt_read_msr(unsigned int msr)
```

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578878668,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578886278,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578892101,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897526,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905182,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578922190,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578924793,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930444,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931125,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578934389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578936548,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071578949269,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578957003,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960198,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972358,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974143,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980101,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579041687,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579049077,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049987,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609052331,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053145,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ]
    },
    {
      "addr": 18446744071609067642,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:detect_art"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105929,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109517,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init"
      ]
    },
    {
      "addr": 18446744071579136409,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150730,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154544,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579158738,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609077798,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161787,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164153,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits"
      ]
    },
    {
      "addr": 18446744071579166917,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167317,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170148,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174549,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:hygon_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174816,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579175552,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ]
    },
    {
      "addr": 18446744071579186976,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192883,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197680,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204953,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609080646,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:set_num_var_ranges"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216117,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ]
    },
    {
      "addr": 18446744071579218683,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ]
    },
    {
      "addr": 18446744071579223211,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229726,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609089910,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253209,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269861,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579285343,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287238,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290933,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ]
    },
    {
      "addr": 18446744071579320064,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322160,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324752,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326800,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338459,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345475,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361957,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385679,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434390,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333350,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585031804,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585128365,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655170,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_init"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:sklh_idle_state_table_update",
        "drivers/idle/intel_idle.c:sklh_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ]
    },
    {
      "addr": 18446744071586073956,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588914997,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588922453,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588940631,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    },
    {
      "addr": 18446744071589081349,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource"
      ]
    },
    {
      "addr": 18446744071591141093,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591141780,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:165",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871104,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578897760,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578930736,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578942632,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579040208,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579050080,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579107056,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579154544,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579162528,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579174816,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579175552,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579215216,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579218683,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579269200,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579288416,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071585654896,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071588928672,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071589080544,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591141072,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u64 paravirt_read_msr(unsigned int msr)
```

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578874748,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578881798,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612080143,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578893254,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900238,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_pmu_disable_fixed"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578921070,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923689,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578931579,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578932309,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578935573,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937732,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071578950869,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958283,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961590,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972022,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976863,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578982261,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579044807,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579052373,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053155,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612115776,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054607,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ]
    },
    {
      "addr": 18446744071591648851,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612131009,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:detect_art"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105561,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109341,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init"
      ]
    },
    {
      "addr": 18446744071579134441,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147834,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151792,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579155874,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612141516,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158843,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161385,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:cpu_set_core_cap_bits"
      ]
    },
    {
      "addr": 18446744071579163605,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164005,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166788,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170933,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:hygon_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171056,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579171808,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ]
    },
    {
      "addr": 18446744071579183168,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_cap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188675,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193328,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200217,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612144393,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:set_num_var_ranges"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210837,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_var_ranges",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ]
    },
    {
      "addr": 18446744071591255678,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ]
    },
    {
      "addr": 18446744071579217179,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223038,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612153557,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246073,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277541,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579292687,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:init_counter_refs",
        "arch/x86/kernel/smpboot.c:init_counter_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293606,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296981,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ]
    },
    {
      "addr": 18446744071579322976,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324848,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326336,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328400,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338464,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343542,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_fault_handler",
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361125,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391135,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433622,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318946,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585183692,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585279645,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781378,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_init",
        "drivers/idle/intel_idle.c:intel_idle_cpu_init"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:sklh_idle_state_table_update",
        "drivers/idle/intel_idle.c:sklh_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ]
    },
    {
      "addr": 18446744071586195412,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588927637,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934901,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588952356,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    },
    {
      "addr": 18446744071612508577,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591225173,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591225865,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:163",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867376,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578893488,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578931920,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591240411,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579043328,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579053248,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579106864,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579151792,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579159760,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579171056,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579171808,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579209936,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591255678,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579276800,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579294448,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071585781104,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071588939920,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591225152,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u64 paravirt_read_msr(unsigned int msr)
```

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876668,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578884262,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889765,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895702,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905547,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578925662,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928313,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578936309,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578937041,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578940421,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942564,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071578955861,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963323,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966917,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979670,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985951,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991388,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579047655,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579057589,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060091,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614256097,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061585,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ]
    },
    {
      "addr": 18446744071591592679,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614271623,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112119,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115981,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init"
      ]
    },
    {
      "addr": 18446744071579140713,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154154,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158160,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579162834,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614281191,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165771,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168424,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup"
      ]
    },
    {
      "addr": 18446744071579170917,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171317,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173588,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178144,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579178896,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579189330,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579195027,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198848,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614284371,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213221,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ]
    },
    {
      "addr": 18446744071591199274,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ]
    },
    {
      "addr": 18446744071579219659,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225358,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614293976,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248057,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280181,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579295359,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:init_counter_refs",
        "arch/x86/kernel/smpboot.c:init_counter_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296278,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299781,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ]
    },
    {
      "addr": 18446744071579326576,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327568,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329056,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331104,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342231,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365509,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394463,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436438,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322418,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065644,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585162797,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585662003,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586071145,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588574361,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588815925,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588825287,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588840809,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    },
    {
      "addr": 18446744071614650834,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591174405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591175097,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867216,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578895936,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578936640,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591183823,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579046128,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579060176,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579113424,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579158160,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579166832,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579178144,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579178896,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579212320,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591199274,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579279504,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579297120,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071585661680,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071588828400,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071591174384,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u64 paravirt_read_msr(unsigned int msr)
```

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879245,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578888314,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891685,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897030,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578908259,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578930558,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933305,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943061,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943883,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578948021,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954197,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071578966405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975827,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979461,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991702,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001919,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008444,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579068807,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579077285,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081243,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615176887,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082865,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ]
    },
    {
      "addr": 18446744071592764503,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615193928,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137290,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init"
      ]
    },
    {
      "addr": 18446744071579167609,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184994,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187584,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579193394,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615204645,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196987,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201432,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup"
      ]
    },
    {
      "addr": 18446744071579204165,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204693,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207108,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211338,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212336,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579213088,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579224340,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230259,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234704,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615208179,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251125,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ]
    },
    {
      "addr": 18446744071592067237,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ]
    },
    {
      "addr": 18446744071579258044,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263967,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615219619,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:check_quirks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288617,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323061,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579342495,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:arch_scale_freq_tick",
        "arch/x86/kernel/smpboot.c:init_counter_refs",
        "arch/x86/kernel/smpboot.c:init_counter_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343542,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344560,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ]
    },
    {
      "addr": 18446744071579381136,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382224,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383840,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386352,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399671,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615272640,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426069,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579456383,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500454,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init",
        "arch/x86/mm/pat/memtype.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580477361,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585512303,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585615981,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586140630,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586565897,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249789,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589509349,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589519303,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589537273,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    },
    {
      "addr": 18446744071615609772,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728405,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592027925,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592028709,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:180",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578868816,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578897264,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071578943424,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071592043463,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579067280,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579081424,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579138672,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579187584,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579198096,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579212336,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579213088,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579249872,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071592067237,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579322544,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579344560,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071586140256,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071589523456,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071592027904,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
u64 paravirt_read_msr(unsigned int msr)
```

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876681,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578889966,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_status",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891336,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb",
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900614,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913726,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_enable_fixed",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578938286,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941702,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951336,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952411,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578956789,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964421,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071578977157,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987815,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993045,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011734,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018551,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026102,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579091721,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071579105061,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109660,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071616942600,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111591,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive"
      ],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ]
    },
    {
      "addr": 18446744071579118118,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616961318,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173744,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179098,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init"
      ]
    },
    {
      "addr": 18446744071579184396,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213192,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232719,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593828399,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579242658,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs",
        "arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616977550,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246139,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251461,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup"
      ]
    },
    {
      "addr": 18446744071579254439,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
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
      "addr": 18446744071579255045,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258275,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262238,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263264,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ]
    },
    {
      "addr": 18446744071579264176,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579275387,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281267,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285969,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616981448,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303301,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ]
    },
    {
      "addr": 18446744071593833666,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ]
    },
    {
      "addr": 18446744071579309741,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316561,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616993447,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:check_quirks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342856,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382741,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579404510,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408853,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ]
    },
    {
      "addr": 18446744071579445946,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447392,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449280,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579452112,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465569,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617048757,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579493477,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499379,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531065,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582105,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:init_cache_modes"
      ]
    },
    {
      "addr": 18446744071580671527,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586662911,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586773404,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587371787,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
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
      "addr": 18446744071587826369,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590716141,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590718289,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590993445,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590998845,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591008287,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591029573,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists"
      ]
    },
    {
      "addr": 18446744071617419747,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591237429,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593795221,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593796468,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865344,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578900976,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071578951840,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593809575,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579091408,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579109920,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579175664,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593828399,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579247328,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579263264,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579264176,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579302080,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593833666,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579382144,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579405600,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579581520,
      "name": "paravirt_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587371360,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071591013056,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593795168,
      "name": "paravirt_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885518,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578898009,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_status",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901475,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_read",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578901704,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb",
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627496135,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:setup_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578913478,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627505207,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578955070,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958758,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967800,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627510165,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973733,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981813,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995813,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007495,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013781,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:mtl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038358,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046183,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054646,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579127417,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143989,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147283,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627550587,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150263,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157557,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627576913,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228064,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627577900,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239372,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269448,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291596,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627596267,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302354,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs",
        "arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627598240,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306091,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312901,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316247,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316901,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320403,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324506,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326060,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327075,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339803,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346387,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352224,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627602939,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369461,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_disable",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627613745,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377575,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382305,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627619351,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411628,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424475,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627627247,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467174,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:cpu_emergency_svm_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579485179,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627659617,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532346,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534288,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536928,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540320,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627690692,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_is_pc10_damaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589493,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579595987,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634265,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627722259,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941959,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587910815,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620299,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589166065,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592387757,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592390036,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592700389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592706477,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592717375,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071628142166,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628173457,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:suspend_hv_clock_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592989253,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "drivers/hv/hv_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv_common.c:__hv_read_ref_counter",
        "drivers/hv/hv_common.c:hv_common_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595738693,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595740484,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595939084,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:186",
      "file": "arch/x86/lib/insn-eval.c",
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883500,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895900,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_status",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578899379,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_read",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900432,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_drain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619240263,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:setup_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578911110,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619244521,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953678,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578957942,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967032,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619255077,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972981,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981125,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995557,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007527,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013829,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:mtl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040184,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046237,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054550,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579127737,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144597,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147843,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619297067,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152375,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159717,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619329116,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233776,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619330382,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245404,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275768,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298094,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304864,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309522,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs",
        "arch/x86/kernel/cpu/aperfmperf.c:init_counter_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619352315,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313259,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320037,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323383,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324037,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328834,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333066,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334620,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335633,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348683,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355267,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361184,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619357212,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378565,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_disable",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619369284,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387111,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390049,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619374896,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400688,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579424028,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436427,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619383375,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_non_nested_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479622,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:cpu_emergency_svm_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497787,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619416577,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545258,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547200,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549760,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579552688,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619448354,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_is_pc10_damaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602037,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579608771,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648313,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619479859,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029095,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184767,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588908043,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459441,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592816609,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592819108,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593131413,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593141677,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593154367,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619909062,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596264677,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596266452,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596457610,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:188",
      "file": "arch/x86/lib/insn-eval.c",
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578905804,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578918396,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_status",
        "arch/x86/events/amd/core.c:amd_pmu_test_overflow_topbit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921971,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_disable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_enable_all",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_read",
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923024,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_drain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621530327,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:setup_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578933652,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621534780,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:init_hybrid_pmu",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977070,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981335,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991816,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_store_lbr",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_32",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_save",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621547653,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997749,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579006101,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020485,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032695,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038757,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:mtl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:adl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:tgl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065140,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071570,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079750,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579154527,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_is_hyperv_initialized",
        "arch/x86/hyperv/hv_init.c:hv_resume",
        "arch/x86/hyperv/hv_init.c:hv_suspend",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177123,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621590555,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:setup_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181671,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:x86_gsbase_read_task",
        "arch/x86/kernel/process_64.c:x86_fsbase_read_task",
        "arch/x86/kernel/process_64.c:__rdgsbase_inactive",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189029,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621621598,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:detect_art"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262624,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621623340,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274364,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_sync_guest_vmexit_xfd_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305576,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327521,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335808,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:update_gds_msr",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340682,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf",
        "arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf",
        "arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf",
        "arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick",
        "arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621646331,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344235,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/feat_ctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities",
        "arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350053,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_verify_msr",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:detect_tme_early",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353287,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_ap_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354344,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360078,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363204,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364700,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365553,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378571,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385203,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_reenable",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_claim_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_skip_bank",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_handle_storm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391056,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621651100,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410069,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_disable",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:set_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621663172,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419341,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621668363,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429232,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579453612,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466011,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621678742,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527627,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621711821,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:x2apic_setup",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id",
        "arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id",
        "arch/x86/kernel/apic/apic.c:check_x2apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579573868,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575472,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579577808,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581392,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621745471,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631797,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579638531,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579672389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/cet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cet.c:do_user_cp_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674172,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/shstk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/shstk.c:wrss_control",
        "arch/x86/kernel/shstk.c:restore_signal_shadow_stack",
        "arch/x86/kernel/shstk.c:setup_signal_shadow_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682169,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621776467,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127303,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588476767,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204827,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589767441,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593565517,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_init_thermal",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593567229,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_do_enable",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:hfi_disable",
        "drivers/thermal/intel/intel_hfi.c:hfi_disable",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593884162,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_exit",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr_each"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593895549,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593908223,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071622219094,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_adjust_perf",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_cpu_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_sample",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:show_energy_efficiency",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/cpufreq/intel_pstate.c:set_power_ctl_ee_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597147365,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597149140,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597352634,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:190",
      "file": "arch/x86/lib/insn-eval.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877390,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881862,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604593458,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578892602,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604596218,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916974,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919561,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923431,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604602560,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928581,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604603514,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942181,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950795,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953398,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964657,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970473,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579033229,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040306,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604631054,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044228,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604647966,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094425,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604649054,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121913,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135596,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604655586,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142562,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604657594,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147659,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149349,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149861,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150276,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156307,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156773,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157573,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168839,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175059,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176470,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184713,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604661053,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193733,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604666734,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200891,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205312,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604670831,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228505,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604673380,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258984,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604691947,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289340,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290192,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291424,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305433,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311359,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328373,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354926,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391510,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580233078,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436812,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909808,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585165957,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587676805,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682447,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605033662,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605054000,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924389,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925540,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589726339,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/insn-eval.c",
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877326,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881798,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604671282,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578892538,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604674042,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578916910,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919497,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923367,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680384,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578928517,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681338,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942117,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950731,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953334,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964593,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970393,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579032813,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037973,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039890,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604708862,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043812,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725729,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093977,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604726817,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121465,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135148,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733349,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142114,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735357,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147211,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148901,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149413,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149828,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155859,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156325,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157125,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168407,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174723,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176134,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184377,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604738816,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194805,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604744497,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201963,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206384,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604748594,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229577,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604751143,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260184,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604769531,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290540,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291392,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292624,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305433,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311279,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328293,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354846,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391430,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580224550,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419724,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911232,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585317805,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588007957,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588013599,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605119440,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605140575,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588257797,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258948,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169715,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/insn-eval.c",
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
  "name": "paravirt_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877678,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578882150,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604671291,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578893018,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604674062,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578917438,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578920041,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923911,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680404,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578929093,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681358,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942693,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951307,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953910,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965185,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970985,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/xen/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579036381,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hv_cpu_die",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041621,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043554,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604708878,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047540,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725775,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098217,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604726863,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126585,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140268,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733395,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147250,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735403,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152347,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154037,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154549,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154964,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160995,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161461,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162261,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173591,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179907,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181318,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189625,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604738862,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200053,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604744543,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207243,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211664,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604748640,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234985,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:__rmid_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604751176,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265784,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604769788,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296428,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297312,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_uv_x.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300224,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301456,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313651,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319599,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336581,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363294,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399958,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277318,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525772,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017312,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585423949,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123397,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588129071,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/powernow-k8.c:pending_bit_stuck"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605146598,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605168422,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393317,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394468,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590220163,
      "name": "paravirt_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:159",
      "file": "arch/x86/lib/insn-eval.c",
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
u64 paravirt_read_msr(unsigned int msr)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
u64 paravirt_read_msr(unsigned int msr)
```
</details>
</li>
</ul>
