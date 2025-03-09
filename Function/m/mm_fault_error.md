# Function: <code>mm_fault_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, unsigned int fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579284032,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:886",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284032,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, unsigned int fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283488,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:977",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283488,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, unsigned int fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298864,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1008",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298864,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, unsigned int fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296688,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1049",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296688,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 * pkey, unsigned int fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317328,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1029",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317328,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 * pkey, unsigned int fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1001",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327952,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071579329993,
      "name": "mm_fault_error.cold.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1069",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352128,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071579356135,
      "name": "mm_fault_error.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1033",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367088,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579370614,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1055",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371328,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579374880,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1021",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400048,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071579403405,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:972",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401808,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071591270001,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282715152,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/powerpc/mm/fault.c:170",
      "file": "arch/powerpc/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/fault.c:__do_page_fault"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1055",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367232,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579370784,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1055",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297712,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579300972,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1055",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367152,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579370704,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```

```json
{
  "name": "mm_fault_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mm_fault_error",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1055",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375584,
      "name": "mm_fault_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071579379184,
      "name": "mm_fault_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address, fault</code> ➡️ <code>regs, error_code, address, vma, fault</code>
</li>
</ul>
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
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * pkey</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 * pkey</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address, pkey, fault</code> ➡️ <code>regs, error_code, address, fault</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int fault</code> ➡️ <code>vm_fault_t fault</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
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
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mm_fault_error(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
