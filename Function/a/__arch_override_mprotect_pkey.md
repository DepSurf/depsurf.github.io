# Function: <code>__arch_override_mprotect_pkey</code>

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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334944,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:67",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:SyS_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334944,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350736,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:90",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350736,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344528,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:90",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344528,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369728,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:89",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369728,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382288,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:89",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382288,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409856,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:89",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409856,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425600,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425600,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428768,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428768,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453712,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453712,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450624,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450624,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453120,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453120,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579518576,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:76",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518576,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602608,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:76",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602608,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715536,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:76",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715536,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729120,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:76",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729120,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579764064,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:76",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579764064,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424608,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424608,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579353744,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353744,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424528,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424528,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```

```json
{
  "name": "__arch_override_mprotect_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433680,
      "name": "__arch_override_mprotect_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:77",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mprotect.c:do_mprotect_pkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433680,
      "name": "__arch_override_mprotect_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
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
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __arch_override_mprotect_pkey(struct vm_area_struct * vma, int prot, int pkey)
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
