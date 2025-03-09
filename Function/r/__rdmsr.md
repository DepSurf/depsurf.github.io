# Function: <code>__rdmsr</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579106072,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:90",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596348190,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:90",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171729,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:90",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177446,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:90",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266832,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:90",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
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
long long unsigned int __rdmsr(unsigned int msr)
```

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119076,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602666413,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189100,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193030,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283521,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370723,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_enable",
        "arch/x86/mm/mem_encrypt.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370723,
      "name": "__rdmsr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579127354,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602837688,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200433,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204484,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294928,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602898742,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134026,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604631674,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189825,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194660,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319616,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604696126,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579144456,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604728910,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202661,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207510,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334848,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604796207,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579146712,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604742023,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204917,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209766,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339056,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604821933,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long long unsigned int __rdmsr(unsigned int msr)
```

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579164863,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591158218,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609087867,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225868,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230918,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368768,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579456115,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456115,
      "name": "__rdmsr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579162095,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591652022,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612151085,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219820,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224358,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367776,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591265392,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev-es.c:sev_es_rd_ghcb_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612230792,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579168895,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591595878,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614291580,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222300,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226758,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372000,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591207597,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:sev_es_rd_ghcb_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614371516,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579201915,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592767974,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615217663,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261110,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265414,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433264,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592081013,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:sev_es_rd_ghcb_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615303599,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:89",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103573,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol",
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579227805,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252248,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594661621,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616991357,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312950,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317532,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502256,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525844,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:__sev_cpuid_hv",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617084004,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060895,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070591,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140725,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol",
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286488,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314049,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395813,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627616114,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377977,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383724,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424206,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599632,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579626164,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:__sev_cpuid_hv",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627739833,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596907609,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb",
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060767,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070415,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141669,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol",
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293064,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321190,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596926773,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619371730,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387350,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393116,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436158,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612320,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579640116,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:__sev_cpuid_hv",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619498889,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593348944,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
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
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597833161,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/events/amd/brs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/brs.c:perf_amd_brs_lopwr_cb",
        "arch/x86/events/amd/brs.c:amd_pmu_brs_sched_task",
        "arch/x86/events/amd/brs.c:amd_brs_drain",
        "arch/x86/events/amd/brs.c:amd_brs_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085855,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095631,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169763,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_snp_boot_ap",
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol",
        "arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322328,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:ppin_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579351125,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597852453,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621665501,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417912,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info",
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621667809,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465742,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642032,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669945,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:__sev_cpuid_hv",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621795721,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594102944,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:80",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_msr_cs",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_tsc",
        "drivers/clocksource/hyperv_timer.c:read_hv_clock_tsc_cs"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147080,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604668326,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203765,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208614,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334960,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735813,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578868096,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578875739,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604585087,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071578886810,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_start",
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894971,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578912318,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915161,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071578919561,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071578921836,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925301,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930661,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071578939170,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948032,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951158,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958880,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964453,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972533,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973177,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604599079,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973248,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604615851,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026413,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579029475,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053845,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066079,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604623313,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073877,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604625355,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079835,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080837,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081592,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083122,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579087163,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579088400,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089194,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100473,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579107206,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579111572,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579117721,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071604628751,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129029,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579131818,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604635930,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138715,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143384,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604638527,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163947,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179957,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194233,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198005,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224547,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579226016,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228176,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239877,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245839,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262759,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287151,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071579321070,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604703434,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180570,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372112,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816164,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080169,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587453253,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071587461957,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605001345,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071605020010,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605022316,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/vmbus_drv.c:hv_acpi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587560277,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071587640309,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640734,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
      "addr": 18446744071589452084,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579146632,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604746089,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204837,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209686,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334880,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813380,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
  "name": "__rdmsr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579151768,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604746135,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210117,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214966,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343232,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604826090,
      "name": "__rdmsr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
long long unsigned int __rdmsr(unsigned int msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long long unsigned int __rdmsr(unsigned int msr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long long unsigned int __rdmsr(unsigned int msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long long unsigned int __rdmsr(unsigned int msr)
```
</details>
</li>
</ul>
