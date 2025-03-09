# Function: <code>cpuid_eax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594957220,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105641,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106918,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109677,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113903,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118279,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120558,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127612,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595012752,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
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
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164980,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
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
      "addr": 18446744071595022264,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254647,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585885997,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595331756,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:524",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595120803,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105450,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106505,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108986,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113695,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119423,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120462,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127761,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595177389,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
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
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165380,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
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
      "addr": 18446744071595187063,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253660,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290932,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595519118,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:535",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595363549,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103994,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105177,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107478,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112239,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118205,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119166,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134849,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595420601,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
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
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175236,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595429681,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267148,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586495156,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595775186,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:577",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596281795,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596293003,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095596,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096712,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099142,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106634,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110247,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111193,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133556,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596340702,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596348023,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579170665,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174980,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596350058,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263772,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586619967,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596706239,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:588",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578886157,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071602610826,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579106741,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107880,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114037,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120466,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122534,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124601,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148436,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175873,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/mtrr/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071602666121,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186073,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192836,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194518,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579280668,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584851725,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587104266,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603036951,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578886157,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579175873,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579194518,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578887877,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071602779135,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579112793,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114069,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120408,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128022,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132220,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133307,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158373,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187136,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071602837403,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579197566,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204379,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579206430,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579292023,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080365,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587400837,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603209630,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:626",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887877,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579187136,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579206430,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578887733,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071604572963,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118617,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119733,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126168,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134698,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139121,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140672,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579142139,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147861,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176512,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071604631389,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187070,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194555,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230019,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579317063,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192221,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587581205,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605020089,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:621",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578887733,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579176512,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579230019,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578888901,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071604668068,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128102,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128840,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135769,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145697,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150561,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152352,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579153851,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154651,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160485,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189008,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071604728618,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199774,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207403,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579243330,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579332311,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585403659,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587854266,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605133305,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578888901,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579189008,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579243330,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578889953,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071604680596,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129974,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130712,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137705,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148238,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153124,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154912,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579156347,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157147,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162949,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191296,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071604741731,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201998,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209659,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579245522,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579336487,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585545419,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588059082,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605173650,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578889953,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579191296,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579245522,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578894689,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071609031264,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145881,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146616,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153417,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165943,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168336,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173180,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175433,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176233,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591158416,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579211995,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071609088015,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223166,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229371,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270014,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579365893,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586262869,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_need_v2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588923864,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609457403,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:645",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578894689,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579211995,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579270014,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591239766,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071612094661,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142971,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143672,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151065,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163191,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164944,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169612,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579171689,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172489,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591652304,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591254932,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071612151778,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217134,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222875,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257544,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579365045,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586381141,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_need_v2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588936296,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612533558,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:628",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591239766,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591254932,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591257544,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591182566,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071614234832,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149323,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150024,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157433,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170721,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171760,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178046,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579178777,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179245,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591596160,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591198536,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071614291396,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219614,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225195,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591200890,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579369269,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586266606,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824232,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614676228,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:610",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182566,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591198536,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071591200890,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592039609,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071615154308,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176843,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178442,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186793,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203969,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205204,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212238,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579212969,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213437,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592769558,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592066138,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071615217447,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258011,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263755,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592071274,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ]
    },
    {
      "addr": 18446744071579430261,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586777118,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518098,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615636777,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592039609,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071592066138,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071592071274,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593805774,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071593813443,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ]
    },
    {
      "addr": 18446744071579180393,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223211,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225018,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232624,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253873,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257333,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263141,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264032,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264597,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273435,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593832622,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071616991112,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309698,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316355,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837631,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_msi_ext_dest_id",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ]
    },
    {
      "addr": 18446744071579498773,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588055757,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591007357,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617449650,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:622",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593805774,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071593813443,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071593832622,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071593837631,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627495980,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627520033,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579235385,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280555,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283258,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291534,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:check_null_seg_clears_base",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315665,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319413,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325429,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326272,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326773,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337627,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627603068,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627615748,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377474,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381975,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627625103,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
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
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460231,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579595205,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589435568,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628040450,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592715168,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628214335,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619240108,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923702,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619265217,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619278493,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data",
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579241299,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286217,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289770,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295050,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322801,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327269,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333991,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334832,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335333,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346507,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619371401,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387010,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389719,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619381199,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
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
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472807,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607989,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589734704,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619805938,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593152048,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619983295,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621530172,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953287,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:init_hybrid_pmu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621557889,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:msi_ext_dest_id",
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621571469,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data",
        "arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270147,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316029,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319034,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324362,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352705,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356981,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_detect_tlb_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364071,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:cpu_detect_tlb_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364912,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365253,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376507,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416836,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419047,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621676431,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
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
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503095,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637749,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590074512,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622114418,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593905600,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622295882,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:94",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_hvm_msi_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578889953,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071604606901,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130358,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131096,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138073,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148606,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153492,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155280,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579156715,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157515,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163301,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190144,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071604668034,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200846,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208507,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579244370,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579332391,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307451,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587684074,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605062294,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578889953,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579190144,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579244370,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604585033,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061663,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062481,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069265,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076687,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084996,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086232,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579088238,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089026,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094817,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604628567,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604635141,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135816,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141145,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604640538,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071604674002,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459437,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578889889,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071604684692,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129910,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130648,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137625,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148158,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153044,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154832,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579156267,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157067,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162869,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191216,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071604745797,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201918,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209579,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579245442,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579332311,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585495819,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588015226,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605149853,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578889889,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579191216,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579245442,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```

```json
{
  "name": "cpuid_eax",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578890341,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ]
    },
    {
      "addr": 18446744071604684648,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135030,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135768,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142761,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153294,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158180,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159968,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579161403,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162203,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168053,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196464,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ]
    },
    {
      "addr": 18446744071604745843,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207198,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214859,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579250994,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579340615,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585603851,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588130698,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu",
        "drivers/cpufreq/powernow-k8.c:check_supported_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605177844,
      "name": "cpuid_eax",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:611",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_msi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578890341,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579196464,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579250994,
      "name": "cpuid_eax",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
unsigned int cpuid_eax(unsigned int op)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
unsigned int cpuid_eax(unsigned int op)
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
unsigned int cpuid_eax(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int cpuid_eax(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int cpuid_eax(unsigned int op)
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
unsigned int cpuid_eax(unsigned int op)
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
