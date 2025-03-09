# Function: <code>do_kern_addr_fault</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579351632,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1263",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351632,
      "name": "do_kern_addr_fault",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579369120,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1227",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369120,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373360,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1249",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373360,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402368,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1215",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402368,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579403904,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1178",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403904,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579407088,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1140",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407088,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579469648,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1147",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469648,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579546528,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1147",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546528,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579649232,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1178",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649232,
      "name": "do_kern_addr_fault",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663632,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1152",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663632,
      "name": "do_kern_addr_fault",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579697632,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1157",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697632,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579369264,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1249",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369264,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579297296,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1249",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297296,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579369184,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1249",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369184,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_kern_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579377616,
      "name": "do_kern_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1249",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377616,
      "name": "do_kern_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
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
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_kern_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
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
