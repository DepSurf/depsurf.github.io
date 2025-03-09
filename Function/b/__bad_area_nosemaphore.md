# Function: <code>__bad_area_nosemaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283344,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:763",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_nosemaphore",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_access_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283344,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579282688,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:823",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282688,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298064,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:854",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298064,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct * vma, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579295904,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:895",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295904,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 * pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316448,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:871",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316448,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 * pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:843",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327136,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071579329895,
      "name": "__bad_area_nosemaphore.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:901",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351152,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071579356026,
      "name": "__bad_area_nosemaphore.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:866",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366288,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071579370516,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:888",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370528,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071579374782,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:852",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399312,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071579403304,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:801",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401024,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071591269896,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:795",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404032,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    },
    {
      "addr": 18446744071591212413,
      "name": "__bad_area_nosemaphore.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:800",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466544,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071592086607,
      "name": "__bad_area_nosemaphore.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:800",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543248,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071593853405,
      "name": "__bad_area_nosemaphore.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648448,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:831",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648448,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662848,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:811",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662848,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696848,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:802",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696848,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
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
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282712448,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/powerpc/mm/fault.c:83",
      "file": "arch/powerpc/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/fault.c:bad_access",
        "arch/powerpc/mm/fault.c:bad_area",
        "arch/powerpc/mm/fault.c:bad_area_nosemaphore"
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:888",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366432,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071579370686,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:888",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296768,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071579300874,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:888",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366352,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071579370606,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```

```json
{
  "name": "__bad_area_nosemaphore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bad_area_nosemaphore",
      "external": false,
      "loc": "arch/x86/mm/fault.c:888",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area",
        "arch/x86/mm/fault.c:bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374784,
      "name": "__bad_area_nosemaphore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071579379086,
      "name": "__bad_area_nosemaphore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<code>regs, error_code, address, si_code</code> ➡️ <code>regs, error_code, address, vma, si_code</code>
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
<b>Param type changed. </b>
<code>u32 * pkey</code> ➡️ <code>u32 pkey</code>
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
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bad_area_nosemaphore(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, u32 pkey, int si_code)
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
