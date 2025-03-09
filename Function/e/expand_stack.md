# Function: <code>expand_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705632,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2333",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/mmap.c:find_extend_vma",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705632,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823088,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2230",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/mmap.c:find_extend_vma",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823088,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888592,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2383",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "mm/mmap.c:find_extend_vma",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888592,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580933555,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2426",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933488,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581033315,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2442",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033248,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581167923,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2502",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167856,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581247971,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2536",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247904,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322594,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2538",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322512,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581381938,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381856,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581576290,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2541",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576368,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581621796,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2607",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621872,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648164,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2611",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648096,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581916276,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2581",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916208,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582322771,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2602",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322688,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582823653,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2118",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823520,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * expand_stack(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583038416,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2243",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583038416,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
struct vm_area_struct * expand_stack(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583220224,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2246",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:__access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220224,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492788968,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/arm64/mm/fault.c:do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492788832,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226604360,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/arm/mm/fault.c:do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226604248,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286158440,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286158304,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272759370,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/riscv/mm/fault.c:do_page_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272759248,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581350786,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350704,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294498,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294416,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341986,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341904,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int expand_stack(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "expand_stack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581405922,
      "name": "expand_stack",
      "external": true,
      "loc": "mm/mmap.c:2543",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405840,
      "name": "expand_stack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct vm_area_struct *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
