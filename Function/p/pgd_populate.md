# Function: <code>pgd_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594996393,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:120",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358529,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:120",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071580674565,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:120",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361969,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:120",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358529,
      "name": "pgd_populate.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595159878,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365401,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071595243458,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580788799,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587863455,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365401,
      "name": "pgd_populate.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595402453,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383503,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071595487500,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853167,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588078161,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383503,
      "name": "pgd_populate.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394176,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:174",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071581515680,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:174",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071581800318,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:174",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394176,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071579394371,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581515680,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071581800318,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591266756,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:136",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071581560528,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:136",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071591332713,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:136",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266756,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071591266951,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581560528,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071591332713,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591209076,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:136",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071581584560,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:136",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071591275413,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:136",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591209076,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071591209276,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581584560,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071591275413,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592082780,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071581850256,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071592216112,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082780,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071592082980,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071581850256,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071592216112,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593849973,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071593969300,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582242256,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071593994814,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593849973,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071593850183,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071593969300,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071582242256,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071593994814,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596438025,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071582634864,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582732928,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071583153248,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638864,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071582634864,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071582732928,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071583153248,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596978835,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071582844064,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582949408,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071583363680,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652912,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071582844064,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071582949408,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071583363680,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597907267,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:populate_extra_pmd"
      ]
    },
    {
      "addr": 18446744071583018592,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071583128880,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__p4d_alloc"
      ]
    },
    {
      "addr": 18446744071583600352,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:134",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686416,
      "name": "pgd_populate.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    },
    {
      "addr": 18446744071583018592,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071583128880,
      "name": "pgd_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071583600352,
      "name": "pgd_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490459496,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:81",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:stage2_get_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492750992,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503922572,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/arm64/include/asm/pgalloc.h:81",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pgd_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282773260,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:88",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286110248,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:88",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297818320,
      "name": "pgd_populate",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgalloc.h:88",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pgd_populate(struct mm_struct * mm, pgd_t * pgd, p4d_t * p4d)
```
</details>
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
