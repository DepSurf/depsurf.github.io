# Function: <code>__execute_only_pkey</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334848,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:22",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334848,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350480,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:23",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350480,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344272,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:23",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344272,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369472,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:22",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369472,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382032,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:22",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382032,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409600,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:22",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409600,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425344,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425344,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579428512,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428512,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579453456,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453456,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450368,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450368,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452864,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452864,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:14",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592092266,
      "name": "__execute_only_pkey.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579518240,
      "name": "__execute_only_pkey",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:14",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593859356,
      "name": "__execute_only_pkey.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071579602272,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:14",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595971326,
      "name": "__execute_only_pkey.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579715136,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:14",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596488909,
      "name": "__execute_only_pkey.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071579728768,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:14",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597385531,
      "name": "__execute_only_pkey.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071579763712,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424352,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424352,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579353488,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353488,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424272,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424272,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
```

```json
{
  "name": "__execute_only_pkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433424,
      "name": "__execute_only_pkey",
      "external": true,
      "loc": "arch/x86/mm/pkeys.c:15",
      "file": "arch/x86/mm/pkeys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey",
        "mm/mmap.c:do_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433424,
      "name": "__execute_only_pkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int __execute_only_pkey(struct mm_struct * mm)
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
int __execute_only_pkey(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __execute_only_pkey(struct mm_struct * mm)
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
