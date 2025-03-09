# Function: <code>__cpuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879122,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594957220,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594958883,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594965573,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578959021,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_read_msr_safe",
        "arch/x86/xen/enlighten.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002480,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595004340,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356489,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101744,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106829,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107131,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108514,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/common.c:cpu_detect",
        "arch/x86/kernel/cpu/common.c:cpu_detect",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113917,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117434,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120558,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126796,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595012752,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160752,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164980,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595021914,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595022264,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172797,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173224,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227693,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251432,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579254065,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595229992,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583885545,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595251263,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "drivers/xen/xen-acpi-processor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584086236,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_raw_console_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585885997,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595331654,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:35",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879820,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595120803,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595122406,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595129319,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595132516,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999567,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595167938,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595170937,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105464,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106413,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106715,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109877,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113709,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119243,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120462,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127761,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595177389,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160809,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165380,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595186708,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595187063,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173165,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174106,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227958,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250523,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579253667,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595408209,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584216281,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584417055,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_raw_console_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290946,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595519005,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879884,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595363549,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595365157,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595372129,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595375169,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001409,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595410610,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595413289,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104008,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105085,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105387,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108409,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112253,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117933,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119166,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381557,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_get_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134849,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595420601,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170857,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175236,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595429326,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595429681,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183613,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184458,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240371,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264073,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579267155,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595658124,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584397714,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599455,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_raw_console_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586495170,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595775073,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879036,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596281795,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596283602,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596290268,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578958358,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578962812,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596301572,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596307947,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh",
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596330038,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596332712,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095610,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096625,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096923,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100110,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106648,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109980,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111193,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113996,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133556,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596340702,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596348037,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579170665,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174980,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596349718,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596350058,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182365,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183194,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185459,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236403,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260762,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579263779,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596580474,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584480423,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681996,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_raw_console_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586619981,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596706126,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:25",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879931,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting",
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886165,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602599951,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602607046,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578961670,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578966060,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602619385,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602625947,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh",
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602648228,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602650883,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106755,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/intel_cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107793,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108091,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114037,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120480,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122534,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124601,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127388,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148436,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175881,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602666135,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186073,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192836,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602667879,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602668588,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197805,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198810,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201126,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252838,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277610,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579280675,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602908448,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584851850,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584890695,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585091493,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587104280,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603036838,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881772,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578887918,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602768316,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602775379,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602779152,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968644,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602786594,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602794837,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh",
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602818219,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602820833,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112815,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114144,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114489,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120452,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128044,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602825955,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131595,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579133329,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
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
      "addr": 18446744071602826942,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init",
        "arch/x86/kernel/cpu/intel_rdt.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158373,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187177,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602837425,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197584,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204393,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602839145,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602839827,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209774,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211675,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213014,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264287,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288901,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292718,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297999,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071603080385,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080330,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585121716,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585328217,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_raw_console_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587400859,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603209573,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:26",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578881548,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578887774,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604562748,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604570211,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604572980,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966734,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604580674,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604589037,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604594790,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604613358,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604615977,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118639,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119808,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120153,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126212,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134720,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604621711,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138287,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579141317,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142161,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
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
      "addr": 18446744071579147861,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176553,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604631411,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187088,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194569,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604633474,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604635554,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604636257,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233406,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234363,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236694,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288879,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313038,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579317758,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322607,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604882657,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192186,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585232485,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585448526,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587581227,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605020032,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578882716,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578888942,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604656685,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604664797,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604668085,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973808,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604675972,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684409,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690436,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604709240,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604712308,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128124,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128859,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129454,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135813,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145719,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604718718,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149912,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579152997,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153873,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
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
      "addr": 18446744071579154673,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160485,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189049,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728640,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199792,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207417,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604730718,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732798,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733541,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734083,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246702,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248720,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250110,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305263,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328159,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332974,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337978,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604990148,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585403781,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585444625,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665082,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587854288,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605133245,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883740,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889994,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604669084,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604677295,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680613,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976208,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688440,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604696841,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702732,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604721640,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604724141,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129996,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130731,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131326,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137749,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148260,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604731529,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152368,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579155557,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156369,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
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
      "addr": 18446744071579157169,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162949,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191337,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604741753,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202016,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209673,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604743831,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604746041,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604746925,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604747472,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249102,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250880,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251838,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604776187,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309359,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332207,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334510,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342154,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605027416,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585545541,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585585057,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806058,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588059104,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605173590,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578889546,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894730,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609019620,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942619,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071609029366,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980970,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ]
    },
    {
      "addr": 18446744071578984300,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_arch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998504,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities"
      ]
    },
    {
      "addr": 18446744071579021194,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ]
    },
    {
      "addr": 18446744071609050999,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104578,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:detect_art"
      ]
    },
    {
      "addr": 18446744071579124011,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:setup_xstate_features",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ]
    },
    {
      "addr": 18446744071579145903,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146635,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147193,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153461,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165965,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609078445,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168350,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173835,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:hygon_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175455,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176255,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591158416,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212036,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609088037,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223184,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229385,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234479,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ]
    },
    {
      "addr": 18446744071579269185,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ]
    },
    {
      "addr": 18446744071579269922,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ]
    },
    {
      "addr": 18446744071609093498,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273470,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275127,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275927,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323418,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits",
        "arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits",
        "arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits"
      ]
    },
    {
      "addr": 18446744071579338297,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579361686,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579364044,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371455,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585655419,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:sklh_idle_state_table_update"
      ]
    },
    {
      "addr": 18446744071586262834,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_need_v2",
        "drivers/xen/grant-table.c:gnttab_need_v2",
        "drivers/xen/grant-table.c:gnttab_need_v2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586300284,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk",
        "drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586536527,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588923886,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591128018,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942619,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071578980970,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071578998504,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579021194,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579102032,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579124011,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579231408,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579269185,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579269922,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579323418,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071585655419,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591128018,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578885338,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591239807,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612081921,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612089041,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591240398,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071612092743,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591241905,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ]
    },
    {
      "addr": 18446744071578986060,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_arch_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242673,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities"
      ]
    },
    {
      "addr": 18446744071591242946,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ]
    },
    {
      "addr": 18446744071612114387,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104770,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc.c:detect_art"
      ]
    },
    {
      "addr": 18446744071579121624,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:xfeature_size"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:get_xsaves_size",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:setup_xstate_features",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ]
    },
    {
      "addr": 18446744071579142993,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143691,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144249,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151109,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163213,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612142181,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164958,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:amd_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169947,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:hygon_get_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171711,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172511,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591652304,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591254973,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612151800,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217152,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222889,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227631,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ]
    },
    {
      "addr": 18446744071591257420,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ]
    },
    {
      "addr": 18446744071612155145,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257439,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ]
    },
    {
      "addr": 18446744071591257452,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ]
    },
    {
      "addr": 18446744071612158360,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280798,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282376,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283127,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591261614,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits",
        "arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits",
        "arch/x86/kernel/apic/x2apic_uv_x.c:set_x2apic_bits"
      ]
    },
    {
      "addr": 18446744071579338302,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360854,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579363068,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370454,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591429583,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:sklh_idle_state_table_update"
      ]
    },
    {
      "addr": 18446744071586381106,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_need_v2",
        "drivers/xen/grant-table.c:gnttab_need_v2",
        "drivers/xen/grant-table.c:gnttab_need_v2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586418988,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk",
        "drivers/xen/xenbus/xenbus_xs.c:xen_strict_xenbus_quirk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586647743,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588936318,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591641731,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:94",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591240398,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591241905,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591242673,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591242946,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579102208,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579120864,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579224560,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591257420,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591257439,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591257452,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591261614,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591429583,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591641731,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578887868,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591182607,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614220369,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614228552,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591183810,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071614232778,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591184975,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ]
    },
    {
      "addr": 18446744071578996843,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185737,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    },
    {
      "addr": 18446744071591186449,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ]
    },
    {
      "addr": 18446744071614253912,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614255169,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614271600,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127848,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:xfeature_size"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:get_xsaves_size",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ]
    },
    {
      "addr": 18446744071579149345,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150043,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150601,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157477,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:generic_identify",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170743,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614282064,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175674,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177495,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178799,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179267,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591596160,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591198577,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614291418,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219632,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225209,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229983,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ]
    },
    {
      "addr": 18446744071591200766,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ]
    },
    {
      "addr": 18446744071614295159,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591200785,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ]
    },
    {
      "addr": 18446744071591200798,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ]
    },
    {
      "addr": 18446744071614298810,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283550,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285560,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286695,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591204684,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift"
      ]
    },
    {
      "addr": 18446744071579342078,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365238,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579367276,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374198,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591370938,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    },
    {
      "addr": 18446744071586266571,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586309301,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586531711,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588824254,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591585273,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183810,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591184975,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185737,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591186449,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579127264,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579226960,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591200766,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591200785,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591200798,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591204684,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591370938,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591585273,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592039650,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615138777,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615147174,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592043450,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071615151712,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592046820,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ]
    },
    {
      "addr": 18446744071579014438,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592047909,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    },
    {
      "addr": 18446744071592049412,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ]
    },
    {
      "addr": 18446744071615174578,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615176049,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615193905,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153864,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:xfeature_size"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:get_xsaves_size",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ]
    },
    {
      "addr": 18446744071579176865,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178461,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179049,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186837,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203991,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615205714,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209265,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211486,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212991,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213459,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592769558,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592066179,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615217469,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258018,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263770,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268799,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ]
    },
    {
      "addr": 18446744071592070621,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ]
    },
    {
      "addr": 18446744071615221550,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592070977,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ]
    },
    {
      "addr": 18446744071592071182,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ]
    },
    {
      "addr": 18446744071615225673,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327186,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329333,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330439,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592075966,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift"
      ]
    },
    {
      "addr": 18446744071579399518,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615272605,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425798,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579428140,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435558,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592405496,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    },
    {
      "addr": 18446744071586777083,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586828901,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587070015,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589518120,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592756204,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:107",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592043450,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592046820,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592047909,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592049412,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579152816,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579265616,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592070621,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592070977,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592071182,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592075966,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592405496,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592756204,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616896713,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616899382,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593805829,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616902842,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616911842,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593809537,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ]
    },
    {
      "addr": 18446744071616916670,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593813239,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:cpuid_eax"
      ]
    },
    {
      "addr": 18446744071579033233,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593814387,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities"
      ]
    },
    {
      "addr": 18446744071593815730,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ]
    },
    {
      "addr": 18446744071616940017,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616941670,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616961291,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180437,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197782,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:xfeature_size"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:get_compacted_size",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves"
      ]
    },
    {
      "addr": 18446744071579223255,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225028,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225794,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231099,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253917,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616978855,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257126,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
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
      "addr": 18446744071579263018,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264076,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264641,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273449,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593832677,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616991148,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309712,
      "name": "__cpuid",
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
      "addr": 18446744071579316384,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321335,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ]
    },
    {
      "addr": 18446744071593836860,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ]
    },
    {
      "addr": 18446744071616995500,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837286,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ]
    },
    {
      "addr": 18446744071593837496,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ]
    },
    {
      "addr": 18446744071617000002,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387968,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390088,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390844,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593842535,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift"
      ]
    },
    {
      "addr": 18446744071579465400,
      "name": "__cpuid",
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
      "addr": 18446744071617048723,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593846481,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579497410,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504949,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594270986,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    },
    {
      "addr": 18446744071588055719,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588112704,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373163,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590718049,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591007401,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594644083,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593809537,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593813239,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593814387,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593815730,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579194192,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579317792,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593836860,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593837286,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593837496,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593842535,
      "name": "__cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071594270986,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071594644083,
      "name": "__cpuid.constprop.0",
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627490307,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627493984,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627494979,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627496036,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627498699,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627509276,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627511569,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627515232,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627520299,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_platform_hvm",
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:xen_parse_nopv",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062881,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627532702,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627543724,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627547338,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627549226,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627576886,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235784,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:select_idle_routine"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ]
    },
    {
      "addr": 18446744071627582780,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280599,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283268,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284085,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289921,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315709,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627599806,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319206,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
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
      "addr": 18446744071579325306,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326316,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326817,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337641,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627603089,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627615792,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377488,
      "name": "__cpuid",
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
      "addr": 18446744071579382004,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387431,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627620609,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627621007,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627624067,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627625131,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627627636,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect",
        "arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465536,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467405,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627673615,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627690658,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_is_pc10_damaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589250,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579593250,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603013,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627992789,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589435534,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628040412,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector",
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589498540,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589796317,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071628123128,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_parse_features",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592715212,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628214297,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230480,
      "name": "__cpuid.constprop.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619234355,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619238112,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619239107,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619240164,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619242811,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:init_hybrid_pmu",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619254204,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619256481,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619260144,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619262232,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_time_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619265483,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_platform_hvm",
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:xen_parse_nopv",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062753,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619277598,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data",
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619289862,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619293658,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619295562,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619329089,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241761,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:select_idle_routine"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ]
    },
    {
      "addr": 18446744071619335068,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286261,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289780,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290613,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296541,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322845,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619353870,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327062,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
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
      "addr": 18446744071579333866,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334876,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335377,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346521,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619371445,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387024,
      "name": "__cpuid",
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
      "addr": 18446744071579389748,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397079,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg",
        "arch/x86/kernel/cpu/resctrl/core.c:__rdt_get_mem_config_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619376721,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619377119,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619380163,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619381227,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619383732,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect",
        "arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478016,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479853,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619430879,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619448322,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_is_pc10_damaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601784,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579605858,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579615765,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619758421,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589734670,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619805900,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector",
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589799340,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590101645,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619889768,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_parse_features",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593152092,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619983257,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:113",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236288,
      "name": "__cpuid.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621524536,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/coco/tdx/tdx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/coco/tdx/tdx.c:tdx_early_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621528176,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621529171,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621530228,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621533003,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:init_hybrid_pmu",
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621546732,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621549151,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init",
        "arch/x86/events/intel/pt.c:pt_pmu_hw_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621552816,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621554904,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/xen/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/time.c:xen_time_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621558155,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_platform_hvm",
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:xen_parse_nopv",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087841,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621570942,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data",
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621582358,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621586250,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621587757,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621621528,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:detect_art",
        "arch/x86/kernel/tsc.c:native_calibrate_cpu",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270605,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:select_idle_routine"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ]
    },
    {
      "addr": 18446744071621627740,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:init_xstate_size",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:__xstate_dump_leaves"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316073,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4",
        "arch/x86/kernel/cpu/cacheinfo.c:amd_cpuid4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319044,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319829,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325926,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_ht_early",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352749,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621647886,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356774,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
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
      "addr": 18446744071579363946,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364956,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365297,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
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
      "addr": 18446744071579376521,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416864,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419076,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425527,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621671825,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/sgx/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init",
        "arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621672223,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621675267,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621676459,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621679124,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect",
        "arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579508784,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621727087,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621744406,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:mwait_pc10_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631544,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579636226,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644821,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071622065765,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590074478,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version",
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622114380,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector",
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590135564,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590440925,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071622199512,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_parse_features",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593905644,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622295844,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:117",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init",
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265312,
      "name": "__cpuid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883740,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889994,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604595356,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604603567,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604606918,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976560,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604614721,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604623129,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604629020,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604647943,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604650444,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130380,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131115,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131710,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138117,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148628,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604657832,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152736,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579155925,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156737,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
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
      "addr": 18446744071579157537,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163301,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190185,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604668056,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200864,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208521,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604670134,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604672344,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604673228,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604673775,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579247806,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249584,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250542,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305263,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328111,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330414,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338058,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604932548,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307573,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585347089,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585567050,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587684096,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605062234,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883676,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889930,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604673180,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681391,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684709,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976144,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692536,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700937,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604706828,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725706,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728207,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129932,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130667,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131262,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137669,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148180,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735595,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152288,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579155477,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156289,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
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
      "addr": 18446744071579157089,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162869,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191257,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604745819,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201936,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209593,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604747897,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604750107,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604750991,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249006,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250784,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251742,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305263,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328031,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330334,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337978,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605010004,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585495941,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585535457,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756458,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588015248,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605149793,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578884028,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578890382,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604673200,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604681411,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684665,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976736,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692492,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_platform_pv",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700953,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init",
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604706844,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725752,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728253,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:xfeature_size",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_supervisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135052,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135787,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136382,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early",
        "arch/x86/kernel/cpu/topology.c:check_extended_topology_leaf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142805,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_address_sizes",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:cpu_detect_cache_sizes",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153316,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735641,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157424,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579160613,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161425,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
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
      "addr": 18446744071579162225,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168053,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196505,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604745865,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207216,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214873,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604747943,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:rdt_get_cache_alloc_cfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604750140,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604751024,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_edx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_ebx",
        "arch/x86/kernel/cpu/mshyperv.c:cpuid_eax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604751571,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254574,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256352,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257310,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604780328,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313481,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336319,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338990,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints",
        "arch/x86/kernel/kvm.c:kvm_arch_para_features",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346426,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jailhouse.c:jailhouse_paravirt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605031596,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585603973,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585643441,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/xen/xenbus/xenbus_xs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585864682,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588130720,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605177784,
      "name": "__cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:88",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init",
        "arch/x86/pci/xen.c:xen_msi_init"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
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
void __cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```
</details>
</li>
</ul>
