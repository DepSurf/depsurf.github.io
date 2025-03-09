# Function: <code>native_set_p4d</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579265632,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:133",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265632,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283680,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:219",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283680,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579295088,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:220",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602897239,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:220",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295088,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579319408,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604694623,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319408,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334624,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604794646,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334624,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579338832,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604820369,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338832,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579368528,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609158764,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368528,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367536,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612229362,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367536,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371744,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614370118,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371744,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579433008,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615302093,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433008,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501904,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617082362,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501904,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579599232,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627737605,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599232,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611920,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619496580,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611920,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641632,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621793412,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:142",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641632,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334736,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604734249,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334736,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581791,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002514,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604606857,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234476,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492985,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294644,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306959,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329889,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589494174,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354313,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604701870,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604710188,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257923,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323706,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504626,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587643019,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/power/hibernate.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334656,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604811816,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334656,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "native_set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579343008,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604824526,
      "name": "native_set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:136",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343008,
      "name": "native_set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
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
void native_set_p4d(p4d_t * p4dp, p4d_t p4d)
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
