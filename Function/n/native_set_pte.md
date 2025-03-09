# Function: <code>native_set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594976073,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:53",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256400,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256400,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595138717,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:53",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255521,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255456,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595381399,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:53",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269041,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268976,
      "name": "native_set_pte",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596302553,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:62",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265649,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:62",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265584,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602620323,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:64",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282465,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:64",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602723779,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:64",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:sme_populate_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282416,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293920,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897579,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293872,
      "name": "native_set_pte",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318912,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694971,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201039,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581314045,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318864,
      "name": "native_set_pte",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334112,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794993,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273039,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581424271,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334064,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579338320,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820720,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331881,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581485663,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338272,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579368016,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609159056,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529475,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690955,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367968,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366992,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612229654,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573262,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740569,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366992,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371344,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614370428,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594290,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768850,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371344,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432560,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615302406,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861144,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051506,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432560,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616931819,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501552,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617082680,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256023,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478207,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501552,
      "name": "native_set_pte",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627536443,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579598672,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627737972,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747452,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991381,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598672,
      "name": "native_set_pte",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619283403,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611392,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619497087,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582963574,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202289,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611392,
      "name": "native_set_pte",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621575835,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641168,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621793919,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141192,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437831,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641168,
      "name": "native_set_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334224,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734600,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300729,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581454511,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334176,
      "name": "native_set_pte",
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
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579003231,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010010,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579015779,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604619928,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234166,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491264,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:__set_pte_vaddr",
        "arch/x86/mm/init_64.c:set_pte_init",
        "arch/x86/mm/init_64.c:set_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604691393,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313178,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326980,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:ptep_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339907,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700818,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702221,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964375,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119807,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226572,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260442,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306342,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311809,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331043,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337975,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581396488,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421660,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468679,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504261,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505268,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567604,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589731,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624563,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713846,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189709,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360043,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648547,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589379235,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334144,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812167,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291929,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581445711,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334096,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```

```json
{
  "name": "native_set_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579342496,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pte_at"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824877,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356104,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581510184,
      "name": "native_set_pte",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342448,
      "name": "native_set_pte",
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
void native_set_pte(pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_set_pte(pte_t * ptep, pte_t pte)
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
void native_set_pte(pte_t * ptep, pte_t pte)
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
