# Function: <code>__bad_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579283878,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:826",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_access_error"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579283293,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:892",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579298669,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:923",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579296493,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:964",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317254,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:939",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316912,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327877,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:911",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327536,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579351906,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:958",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579366864,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:923",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579371104,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:945",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399824,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:911",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401472,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:857",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401472,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404464,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:853",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404464,
      "name": "__bad_area",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466976,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:859",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466976,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579543760,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:859",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543760,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649408,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:890",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649408,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663808,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:870",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663808,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579697808,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:861",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697808,
      "name": "__bad_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282712420,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/powerpc/mm/fault.c:103",
      "file": "arch/powerpc/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/fault.c:bad_access",
        "arch/powerpc/mm/fault.c:bad_area"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367008,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:945",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579297488,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:945",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579366928,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:945",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
  "name": "__bad_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375360,
      "name": "__bad_area",
      "external": false,
      "loc": "arch/x86/mm/fault.c:945",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __bad_area(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```
</details>
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
