# Function: <code>setup_clear_cpu_cap</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579116032,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:118",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/hyperv/mmu.c:hyperv_setup_mmu_ops",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116032,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123936,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:118",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123936,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579130592,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:118",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130592,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140848,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:127",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140848,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143088,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:128",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143088,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159760,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:128",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param",
        "arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param",
        "arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param",
        "arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159760,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156784,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:131",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156784,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163760,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:134",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/feat_ctl.c:nosgx",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163760,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194432,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:134",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/feat_ctl.c:nosgx",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194432,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243408,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:137",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/feat_ctl.c:nosgx",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243408,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579303232,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:138",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/xen/setup.c:xen_enable_syscall",
        "arch/x86/xen/setup.c:xen_enable_sysenter",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/feat_ctl.c:nosgx",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303232,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310416,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:140",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/xen/setup.c:xen_enable_syscall",
        "arch/x86/xen/setup.c:xen_enable_sysenter",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/feat_ctl.c:nosgx",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310416,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579341168,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:141",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/xen/setup.c:xen_enable_syscall",
        "arch/x86/xen/setup.c:xen_enable_sysenter",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/xen/enlighten_pv.c:xen_init_capabilities",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/common.c:x86_nofsgsbase_setup",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/feat_ctl.c:nosgx",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/kernel/cet.c:ibt_setup",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341168,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143456,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:128",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143456,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579074736,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:128",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074736,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143008,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:128",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143008,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
```

```json
{
  "name": "setup_clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148144,
      "name": "setup_clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:128",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:setup_noclflush",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:setup_disable_smap",
        "arch/x86/kernel/cpu/common.c:setup_disable_smep",
        "arch/x86/kernel/cpu/common.c:x86_noinvpcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_nopcid_setup",
        "arch/x86/kernel/cpu/common.c:x86_mpx_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/rdrand.c:x86_rdrand_setup",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/apic/apic.c:setup_nolapic",
        "arch/x86/kernel/apic/apic.c:init_apic_mappings",
        "arch/x86/kernel/apic/apic.c:setup_nox2apic",
        "arch/x86/kernel/apic/apic.c:parse_lapic",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148144,
      "name": "setup_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void setup_clear_cpu_cap(unsigned int feature)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void setup_clear_cpu_cap(unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void setup_clear_cpu_cap(unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void setup_clear_cpu_cap(unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void setup_clear_cpu_cap(unsigned int feature)
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
