# Function: <code>cpuid_ebx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579109868,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:533",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126782,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:533",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
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
  "name": "cpuid_ebx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579109863,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:544",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
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
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579108395,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:586",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595429947,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:586",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
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
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596293126,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:597",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596308067,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:597",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100096,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:597",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596350324,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:597",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602610949,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602626067,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111234,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121747,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194599,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071584851904,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194599,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602779249,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:635",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602794898,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:635",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117746,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:635",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130750,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:635",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579206511,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:635",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585080417,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:635",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206511,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604573077,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604589094,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579123412,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137496,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141035,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230100,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585192273,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:630",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230100,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604668182,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684470,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132996,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149183,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152709,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243411,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585403821,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243411,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604680710,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604696902,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134884,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151631,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155269,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245603,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585545581,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245603,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609031366,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609047846,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150666,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171362,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173907,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234376,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270093,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071586262923,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:654",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_need_v2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270093,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612094763,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612111190,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147770,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167874,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_detect_mem_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170019,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227528,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257623,
      "name": "cpuid_ebx",
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
      "addr": 18446744071586381195,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_need_v2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257623,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614234934,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614251030,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614255139,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154090,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:generic_identify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173907,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176867,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229880,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591200969,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
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
      "addr": 18446744071586266659,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:619",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591200969,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615154436,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615171446,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615176019,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183311,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207440,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210715,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268696,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592071353,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
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
      "addr": 18446744071586777171,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592071353,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616899350,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616919784,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616937274,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616941638,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579231055,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259100,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261645,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321202,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593837728,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
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
      "addr": 18446744071588055823,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:631",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593837728,
      "name": "cpuid_ebx",
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
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627493940,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627494935,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627519097,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627543762,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627549182,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289877,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321263,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323901,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387298,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627625745,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589435634,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
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
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619238068,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619239063,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619264281,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619289907,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619295518,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296497,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329116,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332461,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396946,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619381841,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
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
      "addr": 18446744071589734770,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
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
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621528132,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_core_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621529127,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/events/amd/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/lbr.c:amd_pmu_lbr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621556953,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621582403,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621587713,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325882,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358016,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362541,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425394,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_cpu_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621677073,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
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
      "addr": 18446744071590074578,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:103",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_request_version"
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604607015,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604623190,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135268,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151999,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155637,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244451,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585307613,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244451,
      "name": "cpuid_ebx",
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
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579065770,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083552,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086488,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604640627,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604684806,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700998,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134820,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151551,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579155189,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245523,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585495981,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245523,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
```

```json
{
  "name": "cpuid_ebx",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604684762,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_hvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701014,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/xen/enlighten_pvh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pvh.c:xen_pvh_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139940,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156687,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160325,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251075,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071585604013,
      "name": "cpuid_ebx",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:620",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251075,
      "name": "cpuid_ebx",
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
unsigned int cpuid_ebx(unsigned int op)
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
unsigned int cpuid_ebx(unsigned int op)
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
unsigned int cpuid_ebx(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int cpuid_ebx(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int cpuid_ebx(unsigned int op)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int cpuid_ebx(unsigned int op)
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
unsigned int cpuid_ebx(unsigned int op)
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
