# Function: <code>pud_same</code>

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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579320278,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:376",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152529,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:376",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579343366,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:377",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273585,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:377",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579354581,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:384",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422281,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:384",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b)
```

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346885,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579381717,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581508137,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346885,
      "name": "pud_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int pud_same(pud_t pud_a, pud_t pud_b)
```

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362588,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579397189,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617737,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362588,
      "name": "pud_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int pud_same(pud_t pud_a, pud_t pud_b)
```

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366828,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579400501,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688585,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366828,
      "name": "pud_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591184635,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:542",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409765,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:542",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905961,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:542",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591679988,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:597",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410409,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:597",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951209,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:597",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591623581,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:597",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413577,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:597",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976729,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:597",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592796908,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:616",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476457,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:616",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279449,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:616",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594696873,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:649",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579554569,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:649",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763321,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:649",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596435315,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:685",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661300,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:685",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297301,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:685",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596976065,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:697",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675460,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:697",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516376,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:697",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597904497,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:827",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709588,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:827",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710424,
      "name": "pud_same",
      "external": false,
      "loc": "include/linux/pgtable.h:827",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
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
int pud_same(pud_t pud_a, pud_t pud_b)
```

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362732,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579396405,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657321,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362732,
      "name": "pud_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
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
int pud_same(pud_t pud_a, pud_t pud_b)
```

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362652,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579396325,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648633,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362652,
      "name": "pud_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int pud_same(pud_t pud_a, pud_t pud_b)
```

```json
{
  "name": "pud_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371084,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579404821,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pudp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715065,
      "name": "pud_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:383",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pud_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371084,
      "name": "pud_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b)
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
int pud_same(pud_t pud_a, pud_t pud_b)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b)
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
int pud_same(pud_t pud_a, pud_t pud_b)
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
