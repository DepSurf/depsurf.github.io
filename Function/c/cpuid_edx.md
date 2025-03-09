# Function: <code>cpuid_edx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579105043,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:551",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109738,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:551",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117420,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:551",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120616,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:551",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595022338,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:551",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251418,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:551",
      "file": "arch/x86/kernel/amd_nb.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104499,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:562",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109515,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:562",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119581,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:562",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120520,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:562",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595187137,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:562",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250509,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:562",
      "file": "arch/x86/kernel/amd_nb.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103043,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:604",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108053,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:604",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118025,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:604",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119224,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:604",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595429757,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:604",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264059,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:604",
      "file": "arch/x86/kernel/amd_nb.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579094787,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099664,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110072,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111251,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596350134,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579260748,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/kernel/amd_nb.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579105940,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:init_amd_cacheinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110830,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123004,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124702,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194680,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579277596,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194680,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111940,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117093,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130297,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133589,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206592,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579288879,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579292695,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:653",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206592,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579117732,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122757,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137033,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142421,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230181,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579313016,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579317735,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:648",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230181,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127060,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132144,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148395,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154133,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154910,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243492,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579328137,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332951,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243492,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579128932,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134032,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150843,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156629,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157406,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245684,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579332185,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334487,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245684,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579144834,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150436,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170733,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175103,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579175918,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269935,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579361664,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579364021,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269935,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141938,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147540,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167274,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171363,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172174,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257465,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579360832,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579363045,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:655",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257465,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579148290,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153802,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173325,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178451,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179386,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591200811,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579365216,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579367253,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591200811,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579175650,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182805,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206845,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579212643,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213578,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592071195,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579425776,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579428117,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592071195,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221964,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230357,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257963,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263656,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264769,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837534,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071593846445,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579497365,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590718005,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593837534,
      "name": "cpuid_edx",
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
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579279276,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289127,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320059,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325880,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326945,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627625800,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589206,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579593205,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628123084,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_parse_features",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
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
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579285708,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295672,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327915,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334440,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335503,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619381896,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601740,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579605813,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619889724,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_parse_features",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
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
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579315431,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324984,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358829,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364520,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_c3",
        "arch/x86/kernel/cpu/centaur.c:init_c3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365423,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621677128,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631500,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579636181,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622199468,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:121",
      "file": "drivers/thermal/intel/intel_hfi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/intel_hfi.c:hfi_parse_features",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_online"
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579129316,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134416,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151211,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156997,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157774,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244532,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579328089,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330391,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244532,
      "name": "cpuid_edx",
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
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060830,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065072,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082538,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088320,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089116,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604640560,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262522,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604674046,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579128868,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579133968,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150763,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156549,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579157326,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245604,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579328009,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579330311,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245604,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
```

```json
{
  "name": "cpuid_edx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579133988,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139088,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155899,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161685,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162462,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251156,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579336297,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338967,
      "name": "cpuid_edx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_arch_para_hints"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251156,
      "name": "cpuid_edx",
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
unsigned int cpuid_edx(unsigned int op)
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
unsigned int cpuid_edx(unsigned int op)
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
unsigned int cpuid_edx(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int cpuid_edx(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int cpuid_edx(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int cpuid_edx(unsigned int op)
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
unsigned int cpuid_edx(unsigned int op)
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
