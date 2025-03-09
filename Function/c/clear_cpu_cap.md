# Function: <code>clear_cpu_cap</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579115970,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:113",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116016,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579123874,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:113",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123920,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579130530,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:113",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130576,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579140799,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:122",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140832,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143023,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:123",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143072,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579159702,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:123",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:init_speculation_control",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159744,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156726,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:126",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:init_speculation_control",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:amd_detect_ppin",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156768,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579163702,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:129",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163744,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579194374,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:129",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194416,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579243337,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:132",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:init_speculation_control",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243376,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579303129,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:133",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:init_speculation_control",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303184,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579310309,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:135",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:init_speculation_control",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_spectral_chicken",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310368,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579341061,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:136",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:init_speculation_control",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/common.c:ppin_init",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341120,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579143391,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:123",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143440,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579074671,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:123",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074720,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142943,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:123",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142992,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "clear_cpu_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579148079,
      "name": "clear_cpu_cap",
      "external": true,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:123",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/alternative.c:alternatives_enable_smp",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:filter_cpuid_features",
        "arch/x86/kernel/cpu/rdrand.c:x86_init_rdrand",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148128,
      "name": "clear_cpu_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
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
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
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
