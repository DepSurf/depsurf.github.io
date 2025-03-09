# Function: <code>fixup_umip_exception</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291536,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:313",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291536,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1165
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:314",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304894,
      "name": "fixup_umip_exception.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579303632,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1167
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:308",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329428,
      "name": "fixup_umip_exception.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579328048,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1285
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:308",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344715,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579343408,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1213
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:318",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349052,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579347584,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:318",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378762,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579377296,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1372
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265119,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579376656,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591207324,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579380272,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592080643,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579441904,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593847982,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579512032,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611056,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611056,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623664,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623664,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652720,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:336",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652720,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 807
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:318",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344956,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579343488,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:318",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277169,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579275760,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1315
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:318",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344876,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579343408,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
bool fixup_umip_exception(struct pt_regs * regs)
```

```json
{
  "name": "fixup_umip_exception",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fixup_umip_exception",
      "external": true,
      "loc": "arch/x86/kernel/umip.c:318",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353324,
      "name": "fixup_umip_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579351856,
      "name": "fixup_umip_exception",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool fixup_umip_exception(struct pt_regs * regs)
```
</details>
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
bool fixup_umip_exception(struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool fixup_umip_exception(struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool fixup_umip_exception(struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool fixup_umip_exception(struct pt_regs * regs)
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
