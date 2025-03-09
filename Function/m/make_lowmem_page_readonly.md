# Function: <code>make_lowmem_page_readonly</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578986800,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:157",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/mmu.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986800,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983520,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:158",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/mmu.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983520,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578985392,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu.c:158",
      "file": "arch/x86/xen/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/mmu.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578985392,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993536,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:125",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578993536,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578996512,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:125",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578996512,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999872,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:127",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999872,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578998768,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998768,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579006240,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579006240,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579007744,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007744,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579015744,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015744,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579018272,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:125",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018272,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021504,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:125",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021504,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579040208,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:125",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040208,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061600,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:127",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061600,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627535856,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:127",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093184,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619282160,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:143",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092896,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579118688,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:143",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context",
        "arch/x86/xen/smp_pv.c:cpu_initialize_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579118688,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579008096,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008096,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579007680,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579007680,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```

```json
{
  "name": "make_lowmem_page_readonly",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579010816,
      "name": "make_lowmem_page_readonly",
      "external": true,
      "loc": "arch/x86/xen/mmu_pv.c:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd_init",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010816,
      "name": "make_lowmem_page_readonly",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void make_lowmem_page_readonly(void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void make_lowmem_page_readonly(void * vaddr)
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
void make_lowmem_page_readonly(void * vaddr)
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
