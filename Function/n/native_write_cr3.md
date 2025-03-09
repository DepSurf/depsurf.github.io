# Function: <code>native_write_cr3</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594980444,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256128,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256128,
      "name": "native_write_cr3",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595143200,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256156,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255184,
      "name": "native_write_cr3",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595385870,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269692,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268736,
      "name": "native_write_cr3",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266236,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265344,
      "name": "native_write_cr3",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284327,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602723266,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282192,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579370749,
      "name": "native_write_cr3",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579295799,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895512,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602898158,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293680,
      "name": "native_write_cr3",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320439,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692821,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695542,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318672,
      "name": "native_write_cr3",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335671,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604792817,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604795572,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333888,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579339879,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818538,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604821331,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338128,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367856,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417111,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609159649,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:50",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367856,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366880,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417191,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612230247,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366880,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371248,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420236,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614370993,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371248,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432464,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579483788,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615302979,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432464,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501440,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579562999,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617083317,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501440,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598576,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579670583,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627738769,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598576,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611328,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579684535,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619497889,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611328,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641104,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579719047,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621794721,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:52",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641104,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335783,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732418,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735211,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334032,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604568491,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:reset_early_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055162,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579183946,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269079,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604688636,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init.c:init_mem_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331054,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush",
        "arch/x86/mm/tlb.c:load_new_mm_cr3"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700143,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702832,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641240,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335703,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809985,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812778,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333952,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
void native_write_cr3(long unsigned int val)
```

```json
{
  "name": "native_write_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579344083,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822695,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604825488,
      "name": "native_write_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:49",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342304,
      "name": "native_write_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
void native_write_cr3(long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_write_cr3(long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_write_cr3(long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_write_cr3(long unsigned int val)
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
void native_write_cr3(long unsigned int val)
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
