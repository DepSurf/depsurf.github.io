# Function: <code>__native_read_cr3</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579266233,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
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
      "addr": 18446744071579265328,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284324,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602723263,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem",
        "arch/x86/mm/mem_encrypt.c:native_read_cr3_pa"
      ],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt.c:sme_encrypt_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282176,
      "name": "__native_read_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    },
    {
      "addr": 18446744071579370740,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579295796,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895509,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602898087,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293664,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579320436,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604692818,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604695471,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318656,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335668,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604792814,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604795501,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333872,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579339876,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818535,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604821260,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338112,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367840,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417108,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609159588,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:43",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367840,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366864,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417188,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612230186,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366864,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371232,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420233,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614370932,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371232,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432448,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579483785,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615302918,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432448,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501424,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579562996,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617083256,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501424,
      "name": "__native_read_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598544,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579670580,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627738703,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598544,
      "name": "__native_read_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611296,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579684532,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619497823,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611296,
      "name": "__native_read_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641072,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579719044,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_local"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621794655,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:45",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641072,
      "name": "__native_read_cr3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335780,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732415,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604735140,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334016,
      "name": "__native_read_cr3",
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
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604568640,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977418,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269076,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296468,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690478,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330936,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700140,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702761,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640872,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648321,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335700,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809982,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812707,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333936,
      "name": "__native_read_cr3",
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
long unsigned int __native_read_cr3()
```

```json
{
  "name": "__native_read_cr3",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579344080,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822692,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604825417,
      "name": "__native_read_cr3",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:42",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel",
        "arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342288,
      "name": "__native_read_cr3",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long unsigned int __native_read_cr3()
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
long unsigned int __native_read_cr3()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int __native_read_cr3()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int __native_read_cr3()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int __native_read_cr3()
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
long unsigned int __native_read_cr3()
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
