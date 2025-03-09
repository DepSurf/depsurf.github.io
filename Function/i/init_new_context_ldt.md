# Function: <code>init_new_context_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int init_new_context_ldt(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "init_new_context_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050048,
      "name": "init_new_context_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:106",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050048,
      "name": "init_new_context_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int init_new_context_ldt(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "init_new_context_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049152,
      "name": "init_new_context_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:106",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049152,
      "name": "init_new_context_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int init_new_context_ldt(struct task_struct * tsk, struct mm_struct * mm)
```

```json
{
  "name": "init_new_context_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041488,
      "name": "init_new_context_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:107",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041488,
      "name": "init_new_context_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
  "name": "init_new_context_ldt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579400065,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:84",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602905507,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:85",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413671,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:85",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604703667,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:80",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446436,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:80",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604803994,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462814,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604829715,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579489490,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609166937,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:62",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517746,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:62",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612236964,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500366,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614377626,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503713,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615309885,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574484,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617091033,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666983,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627749157,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786628,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:61",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619508693,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:55",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833626,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:55",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621805525,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:55",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579871484,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:55",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604743595,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463154,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604711212,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392114,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604821162,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463074,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
  "name": "init_new_context_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604833872,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495490,
      "name": "init_new_context_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:81",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:mm_init"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int init_new_context_ldt(struct task_struct * tsk, struct mm_struct * mm)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int init_new_context_ldt(struct task_struct * tsk, struct mm_struct * mm)
```
</details>
</li>
</ul>
