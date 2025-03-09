# Function: <code>report_bug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582944752,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:141",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944752,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232096,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:141",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232096,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347152,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:141",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347152,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588197440,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:142",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588197440,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588746112,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746112,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124250,
      "name": "report_bug.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071589123904,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358586,
      "name": "report_bug.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071589358240,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815653,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071589815296,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041973,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071590041600,
      "name": "report_bug",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:144",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036773,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071585036464,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:144",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381322,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071585188464,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:157",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323714,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071585070400,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:157",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341725,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071585517136,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:156",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203328,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071586669120,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595748240,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:213",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595748240,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596272544,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:213",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596272544,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597157280,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:213",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:handle_bug",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597157280,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503802552,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503802552,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236425100,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/traps.c:die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236425100,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297640512,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:program_check_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297640512,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279699658,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap_break"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279699658,
      "name": "report_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644229,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071589643856,
      "name": "report_bug",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589370101,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071589369728,
      "name": "report_bug",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087605,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071590087232,
      "name": "report_bug",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
enum bug_trap_type report_bug(long unsigned int bugaddr, struct pt_regs * regs)
```

```json
{
  "name": "report_bug",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "report_bug",
      "external": true,
      "loc": "lib/bug.c:143",
      "file": "lib/bug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137857,
      "name": "report_bug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071590137456,
      "name": "report_bug",
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
