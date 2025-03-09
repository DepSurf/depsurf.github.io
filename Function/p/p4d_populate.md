# Function: <code>p4d_populate</code>

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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596321915,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:126",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287249,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:126",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071580898351,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:126",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304602,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:126",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286368,
      "name": "p4d_populate.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602639859,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306225,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071581000440,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869956,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304800,
      "name": "p4d_populate.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602809498,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318002,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init"
      ]
    },
    {
      "addr": 18446744071581134055,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248938,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317136,
      "name": "p4d_populate.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604604540,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:151",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342690,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:151",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210487,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:151",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491224,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:151",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604700135,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940278,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286647,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952198,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604712519,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590167830,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345367,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179732,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609059168,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389106,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541719,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591198099,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612122528,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394498,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584903,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692990,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591190571,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ]
    },
    {
      "addr": 18446744071579397330,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607143,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635488,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:115",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190571,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592054780,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ]
    },
    {
      "addr": 18446744071579459554,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874263,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592809456,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592054780,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593821641,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ]
    },
    {
      "addr": 18446744071579535465,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165558,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272505,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594710653,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593821641,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579199088,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ]
    },
    {
      "addr": 18446744071596437974,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627851783,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764569,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596455964,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199088,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579203136,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ]
    },
    {
      "addr": 18446744071596978754,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628679,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980943,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596997292,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203136,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void p4d_populate(struct mm_struct * mm, p4d_t * p4d, pud_t * pud)
```

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621602876,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597907186,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583010992,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071583125664,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__pud_alloc"
      ]
    },
    {
      "addr": 18446744071583600160,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:113",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583010992,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583125664,
      "name": "p4d_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071583600160,
      "name": "p4d_populate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604638809,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770118,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314215,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589782020,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604606804,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492998,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257885,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504577,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716601,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590213526,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305415,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225428,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
  "name": "p4d_populate",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716631,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590263894,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:fill_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369415,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275786,
      "name": "p4d_populate",
      "external": false,
      "loc": "arch/x86/include/asm/pgalloc.h:138",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void p4d_populate(struct mm_struct * mm, p4d_t * p4d, pud_t * pud)
```
</details>
</li>
</ul>
